# `slab` `0.4.9`

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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
    "/target/debug/build/slab-b0fe9ec70d8d0253",
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
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-12982-1783992626178609391.map",
  "pid": 12982,
  "ppid": 12942,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-12982-1783992626178609391.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "workspace_root": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
      "name": "slab",
      "version": "0.4.9",
      "manifest_path": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "exit_code": 0,
  "kind": "exec",
  "pid": 12982,
  "ppid": 12942,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:1bbdbee66c5729e1:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
  "pid": 12982,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:dc04c87328a0cd72:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "635c4c225823f9098393adfbe52957a558b76807d63ed12bd8ab7086e96854b9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:712c8f69ccede2e8:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "dcee901fb288990a05d819c003f53112835c27eab39ee0e5dc97909f0d6152db",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:17d8afb7177c60dc:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "3cc063a5d755d937c565bace4b91a7561786e13d92de84630bd1cf9dc140edbc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:b1b0d1f5bef17c8a:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "708a93cc98a5edb5beb2465e2ce6595d8a815e92502ed66b314f9853590fe24c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:3f875d545ec90a35:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "c78702ffc2e3f412f523bee44ba378136ec9d361d538c1711005bfd165bacd22",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:808be1dd0802b41f:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "47b0d54a4b6f6763deb4ef565dc977f8fa404a574b064631f7e7ad93c15b0bcc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:71f7359381e9c85a:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "bb84ad501fce4d09c6f5ce406d0afe148aa7c8f3edb6e0809304eb549e11c871",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:328da672cf537f47:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "2d490bf440db62bc5b2ff8153b9e4866abc27e05ea8e514b72a819bc61a967db",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "used:cc:f2dbe51ddf429de6:6585eac08d8bed73:059a274af5b4dd01",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
  "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
  "pid": 12982,
  "sha256": "d8ba05431cccf258e5dc8aca11279a7038deed1ae36828c3efa3f6365cb14165",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "cargo_pkg_name": "slab",
  "cargo_pkg_version": "0.4.9",
  "context_path": "/tmp/native-trace-10402-1783992621011/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-10402-1783992621011/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 12982,
  "ppid": 12942,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
    "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
    "/target/debug/build/slab-b0fe9ec70d8d0253",
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
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
      "kind": "object",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-12982-1783992626178609391.map",
  "pid": 12982,
  "ppid": 12942,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-12982-1783992626178609391.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
  "parsed_event_count": 323,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 325,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " cc               13043  13038    0 /usr/bin/cc -m64 /target/debug/build/slab-b0fe9ec70d8d0253/rustcPBT2ox/symbols.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0tlsyhv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.969   ld.lld           13047  13046    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch2JrLs.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253 ...\n0.969   collect2         13046  13043    0 \n0.972   rust-lld         13047  13046    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch2JrLs.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.972   build-script-bu  13050  12397    0 /target/debug/build/slab-b0fe9ec70d8d0253/build-script-build\n0.980   rustc            13051  13050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n0.989   rustc            13042  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.007   rustc            13057  13050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_99eb19510c85dce3_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.007   rustc            13058  11664    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.050   rustc            13086  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.096   build-script-bu  13106  12561    0 /target/debug/build/slab-b0fe9ec70d8d0253/build-script-build\n1.106   rustc            13107  13106    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.135   rustc            13115  13106    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_4d8483437660ffb9_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/slab-eed7e102b86e9d2e/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.151   rustc            13124  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.159   rustc            13127  12397    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name slab --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.173   rustc            13131  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.192   rustc            13148  12561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name slab --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.207   rustc            13150  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.222   rustc            13157  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.322   rustc            13182  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.338   rustc            13188  11664    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.434   rustc            13218  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.489   rustc            13229  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.500   rustc            13235  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.547   cc               13262  13182    0 /tmp/native-trace-9934-1783992620245/shims/cc -Wl,--version-script=/target/debug/deps/rustcavC97H/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcavC97H/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcavC97H/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.551   cc               13267  13262    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcavC97H/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcavC97H/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcavC97H/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.557   collect2         13269  13267    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcavC97H/raw-dylibs ...\n1.561   ld.lld           13272  13269    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcavC97H/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.565   rust-lld         13272  13269    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n1.615   cc               13331  13188    0 /tmp/native-trace-10036-1783992620315/shims/cc -Wl,--version-script=/target/debug/deps/rustc2O83Gi/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2O83Gi/symbols.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.00x7z5m9oth5mjy0rvnxr7mrk.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.077ownqvpcueidq6jwb55l19w.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0mz6z2561mf68mxslwr4yfxa9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0znw58n8y6gyn9kv52mja79uu.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1hybit02s0bu4qbn6t4vwxtc2.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1i3ntvwuybjtx26mp4jzeyxyy.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1r9dchyq59cmfyvc2gonlfans.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1s7914rt9ctukziehp9m2g0sp.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1sobdcokrw17f9gyf59dqz2fo.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.29zsxjys3de1e9hctxkawbl1a.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.2hjxzvod7juaix7opuypy1nl9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.305qzos0klqsaom3coq1iaeyn.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.32utzn2a3qoad6o5vgfv6h6n8.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3aq1ptjs71fqwi296i98zrpwi.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3brsl01o3jk7obk5yy0bher2x.1ef9ixn.rcgu.o ...\n1.617   cc               13332  13331    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc2O83Gi/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2O83Gi/symbols.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.00x7z5m9oth5mjy0rvnxr7mrk.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.077ownqvpcueidq6jwb55l19w.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0mz6z2561mf68mxslwr4yfxa9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0znw58n8y6gyn9kv52mja79uu.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1hybit02s0bu4qbn6t4vwxtc2.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1i3ntvwuybjtx26mp4jzeyxyy.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1r9dchyq59cmfyvc2gonlfans.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1s7914rt9ctukziehp9m2g0sp.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1sobdcokrw17f9gyf59dqz2fo.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.29zsxjys3de1e9hctxkawbl1a.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.2hjxzvod7juaix7opuypy1nl9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.305qzos0klqsaom3coq1iaeyn.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.32utzn2a3qoad6o5vgfv6h6n8.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3aq1ptjs71fqwi296i98zrpwi.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3brsl01o3jk7obk5yy0bher2x.1ef9ixn.rcgu.o ...\n1.622   collect2         13333  13332    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc2O83Gi/raw-dylibs ...\n1.627   ld.lld           13334  13333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc2O83Gi/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.631   rust-lld         13334  13333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n1.694   cc               13353  13229    0 /tmp/native-trace-9930-1783992620242/shims/cc -Wl,--version-script=/target/debug/deps/rustcdcBLIP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcdcBLIP/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcdcBLIP/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.696   cc               13354  13353    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcdcBLIP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcdcBLIP/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcdcBLIP/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.701   collect2         13355  13354    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcdcBLIP/raw-dylibs ...\n1.705   ld.lld           13356  13355    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcdcBLIP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.705   rust-lld         13356  13355    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n1.886   rustc            13384  10577    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.213   rustc            13468  10679    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n2.402   rustc            13480  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.625   rustc            13546  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.962   sh               13655  2147557   0 /bin/sh -c which ps\n2.962   rustc            13649  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n2.963   which            13655  2147557   0 /usr/bin/which ps\n2.967   sh               13660  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.970   ps               13660  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.014   sh               13687  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.016   cpuUsage.sh      13687  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n3.018   sed              13688  13687    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.021   cat              13689  13687    0 /usr/bin/cat /proc/2240539/stat\n3.026   cat              13693  13687    0 /usr/bin/cat /proc/4193716/stat\n3.030   sleep            13694  13687    0 /usr/bin/sleep 1\n3.108   cc               13702  13468    0 /tmp/native-trace-9202-1783992619475/shims/cc -Wl,--version-script=/target/debug/deps/rustcZBdSft/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZBdSft/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.109   cc               13703  13702    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZBdSft/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZBdSft/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.114   collect2         13706  13703    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZBdSft/raw-dylibs ...\n3.117   ld.lld           13707  13706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZBdSft/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.121   rust-lld         13707  13706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n3.191   rustc            13726  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n3.244   rustc            13731  10679    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=43084314ea826c64 ...\n3.549   cc               13762  13649    0 /tmp/native-trace-10275-1783992620622/shims/cc -Wl,--version-script=/target/debug/deps/rustcfJWUsc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcfJWUsc/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.550   cc               13763  13762    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcfJWUsc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcfJWUsc/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.555   collect2         13765  13763    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcfJWUsc/raw-dylibs ...\n3.556   ld.lld           13766  13765    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcfJWUsc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.559   rust-lld         13766  13765    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n3.673   rustc            13795  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4b8c2419948abb6e ...\n3.692   cc               13799  13726    0 /tmp/native-trace-10179-1783992620472/shims/cc -Wl,--version-script=/target/debug/deps/rustccSz3Dg/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccSz3Dg/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.693   cc               13800  13799    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustccSz3Dg/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccSz3Dg/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.696   collect2         13801  13800    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustccSz3Dg/raw-dylibs ...\n3.697   ld.lld           13802  13801    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustccSz3Dg/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.699   rust-lld         13802  13801    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n3.803   rustc            13824  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5a367b47b03d5dda ...\n3.963   runc             13831  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2511411117 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n3.969   exe              13838  13831    0 /proc/self/exe init\n3.980   curl             13841  13831    0 /usr/bin/curl -f http://localhost:9091/healthz\n4.032   sed              13848  13687    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.035   cat              13849  13687    0 /usr/bin/cat /proc/2240539/stat\n4.036   cat              13851  13687    0 /usr/bin/cat /proc/4193716/stat\n8.802   16               13853  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n8.819   frpc             13853  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.923  runc             13860  3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1247028754 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n10.930  exe              13867  13860    0 /proc/self/exe init\n10.960  curl             13870  13860    0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.598  16               13877  1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n15.601  16               13878  1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n15.772  systemd-coredum  13877  1        0 /usr/lib/systemd/systemd-coredump\n15.774  drkonqi-coredum  13878  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 882-13876-0\n15.786  runc             13880  9210     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 --log-format json --systemd-cgroup kill --all ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208 9\n15.806  runc             13887  9210     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 --log-format json --systemd-cgroup delete ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208\n15.863  runc             13894  9395     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f --log-format json --systemd-cgroup kill --all cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11 9\n15.872  runc             13900  9395     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f --log-format json --systemd-cgroup delete cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11\n16.051  containerd-shim  13914  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 delete\n16.054  runc             13921  13914    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa20 --log-format json delete --force ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208\n16.063  runc             13926  9510     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 --log-format json --systemd-cgroup kill --all d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301 9\n16.070  runc             13932  9510     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 --log-format json --systemd-cgroup delete d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301\n16.074  runc             13939  9469     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529d --log-format json --systemd-cgroup kill --all fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c 9\n16.082  runc             13945  9469     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529d --log-format json --systemd-cgroup delete fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c\n16.102  sh               13954  13951    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth1b7014c\n16.105  ethtool          13955  13954    0 /usr/sbin/ethtool -i veth1b7014c\n16.105  sed              13956  13954    0 /usr/bin/sed -n s/^driver: //p\n16.107  containerd-shim  13958  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f delete\n16.110  runc             13965  13958    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a1 --log-format json delete --force cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11\n16.121  systemd-sysctl   13971  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1b7014c --prefix=/net/ipv4/neigh/veth1b7014c --prefix=/net/ipv6/conf/veth1b7014c --prefix=/net/ipv6/neigh/veth1b7014c\n16.145  systemd-sysctl   13973  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha071b75 --prefix=/net/ipv4/neigh/vetha071b75 --prefix=/net/ipv6/conf/vetha071b75 --prefix=/net/ipv6/neigh/vetha071b75\n16.182  systemd-userwor  13975  50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n16.190  abrt-server      13976  1118     0 /usr/bin/abrt-server -s\n16.192  9                13977  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n16.206  systemd-userwor  13978  50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n16.207  drkonqi-coredum  13977  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n16.220  abrt-handle-eve  13979  13976    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:30:41.527742-7022\n16.236  sh               13980  13979    0 /bin/sh -c abrt-action-save-package-data\\n\n16.238  abrt-action-sav  13980  13979    0 /usr/bin/abrt-action-save-package-data\n16.296  containerd-shim  13986  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 delete\n16.299  runc             13992  13986    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f730 --log-format json delete --force d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301\n16.301  sh               13998  13979    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n16.303  cut              14000  13998    0 /usr/bin/cut -d: -f1\n16.303  cat              14001  13999    0 /usr/bin/cat uid\n16.304  getent           13999  13998    0 /usr/bin/getent passwd 1000\n16.306  lscpu            14002  13998    0 /usr/bin/lscpu\n16.324  sh               14003  13979    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n16.326  containerd-shim  14005  1663     0 \n16.326  runlevel         14004  14003    0 /usr/bin/runlevel\n16.329  runc             14012  14005    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5 --log-format json delete --force fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c\n16.336  systemd-sysctl   14017  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45e7814 --prefix=/net/ipv4/neigh/veth45e7814 --prefix=/net/ipv6/conf/veth45e7814 --prefix=/net/ipv6/neigh/veth45e7814\n16.339  sh               14018  13979    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n16.341  grep             14019  14018    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n16.342  grep             14020  14018    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n16.344  grep             14021  14018    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n16.346  abrt-action-cor  14022  14018    0 /usr/libexec/abrt-action-coredump -x\n16.388  systemd-sysctl   14023  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf64f55b --prefix=/net/ipv4/neigh/vethf64f55b --prefix=/net/ipv6/conf/vethf64f55b --prefix=/net/ipv6/neigh/vethf64f55b\n16.415  abrt-action-gen  14024  14018    0 /usr/bin/abrt-action-generate-core-backtrace\n16.475  abrt-action-ana  14025  14018    0 /usr/bin/abrt-action-analyze-vulnerability\n16.477  sed              14029  14026    0 /usr/bin/sed s/[^0-9]//g\n16.478  grep             14028  14026    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n16.478  eu-readelf       14027  14026    0 /usr/bin/eu-readelf -n coredump\n16.480  gdb              14031  14030    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n16.498  iconv            14032  14031    0 /usr/bin/iconv -l\n16.597  abrt-action-ana  14041  14018    0 /usr/bin/abrt-action-analyze-c\n16.611  eu-unstrip       14042  14041    0 /usr/bin/eu-unstrip --core=./coredump -n\n16.632  abrt-action-lis  14043  14018    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.696  cat              14045  14044    0 /usr/bin/cat executable\n16.698  cat              14046  14044    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:30:41.527742-7022/uid\n16.700  journalctl       14047  14044    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.713  abrt-action-cor  14048  14018    0 /usr/libexec/abrt-action-coredump -r\n16.772  sh               14049  2147557   0 /bin/sh -c which ps\n16.773  which            14049  2147557   0 /usr/bin/which ps\n16.776  abrt-handle-eve  14051  13976    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.776  sh               14050  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.777  ps               14050  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.794  sh               14052  14051    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.795  dbus-send        14052  14051    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.797  sh               14053  14051    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.798  abrt-action-not  14054  14053    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.805  sh               14055  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.807  cpuUsage.sh      14055  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.809  sed              14056  14055    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.810  cat              14057  14055    0 /usr/bin/cat /proc/2240539/stat\n16.811  cat              14058  14055    0 /usr/bin/cat /proc/4193716/stat\n16.812  sleep            14059  14055    0 /usr/bin/sleep 1\n16.850  sh               14060  14054    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.851  reporter-system  14060  14054    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.295  runc             14063  9937     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 --log-format json --systemd-cgroup kill --all cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b 9\n17.303  runc             14069  9937     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 --log-format json --systemd-cgroup delete cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b\n17.465  runc             14075  9028     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 --log-format json --systemd-cgroup kill --all f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e 9\n17.479  containerd-shim  14081  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 delete\n17.482  runc             14087  14081    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36 --log-format json delete --force cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b\n17.484  runc             14093  9028     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 --log-format json --systemd-cgroup delete f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e\n17.542  systemd-sysctl   14099  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0d7e1a1 --prefix=/net/ipv4/neigh/veth0d7e1a1 --prefix=/net/ipv6/conf/veth0d7e1a1 --prefix=/net/ipv6/neigh/veth0d7e1a1\n17.607  runc             14101  9281     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c --log-format json --systemd-cgroup kill --all 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780 9\n17.616  runc             14107  9281     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c --log-format json --systemd-cgroup delete 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780\n17.700  containerd-shim  14113  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 delete\n17.703  runc             14120  14113    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092 --log-format json delete --force f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e\n17.744  systemd-sysctl   14126  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethedfce10 --prefix=/net/ipv4/neigh/vethedfce10 --prefix=/net/ipv6/conf/vethedfce10 --prefix=/net/ipv6/neigh/vethedfce10\n17.814  sed              14128  14055    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.816  cat              14129  14055    0 /usr/bin/cat /proc/2240539/stat\n17.818  cat              14131  14055    0 /usr/bin/cat /proc/4193716/stat\n17.827  containerd-shim  14133  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c delete\n17.831  runc             14140  14133    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c5378 --log-format json delete --force 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780\n17.874  systemd-sysctl   14145  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6402a8f --prefix=/net/ipv4/neigh/veth6402a8f --prefix=/net/ipv6/conf/veth6402a8f --prefix=/net/ipv6/neigh/veth6402a8f\n"
}
```

#### Record 18

```json
{
  "argv": [
    "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 13050,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
  "pid": 13050,
  "ppid": 12397,
  "root_cargo_pid": 12397,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
  "build_script_root_pid": 13050,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 13051,
  "ppid": 13050,
  "root_cargo_pid": 12397,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_build_script_out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_99eb19510c85dce3_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 13050,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 13057,
  "ppid": 13050,
  "root_cargo_pid": 12397,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_build_script_out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 21

```json
{
  "crate": "slab",
  "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "event_id": "bsrun:93e3fdab3db3da61:66f198e27447f3ac:8b19fa83fcf83981",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
  "out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
  "success": true,
  "target": null,
  "version": "0.4.9",
  "_owner": {
    "crate": "slab",
    "version": "0.4.9",
    "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
    "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
  "build_script_root_pid": 13050,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 13051,
  "ppid": 13050,
  "root_cargo_pid": 12397,
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
    "autocfg_99eb19510c85dce3_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 13050,
  "build_script_target_dir": "slab-b0fe9ec70d8d0253",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 13057,
  "ppid": 13050,
  "root_cargo_pid": 12397,
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
  "time": "2026-07-14T01:30:44.068118+00:00",
  "crate": "slab",
  "version": "0.4.9",
  "architecture": "riscv64",
  "duration_seconds": 27.614619561005384,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "manifest_path": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "workspace_root": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
          "name": "slab",
          "version": "0.4.9",
          "manifest_path": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "exit_code": 0,
      "kind": "exec",
      "pid": 12982,
      "ppid": 12942,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:1bbdbee66c5729e1:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
      "pid": 12982,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:dc04c87328a0cd72:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "635c4c225823f9098393adfbe52957a558b76807d63ed12bd8ab7086e96854b9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:712c8f69ccede2e8:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "dcee901fb288990a05d819c003f53112835c27eab39ee0e5dc97909f0d6152db",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:17d8afb7177c60dc:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "3cc063a5d755d937c565bace4b91a7561786e13d92de84630bd1cf9dc140edbc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:b1b0d1f5bef17c8a:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "708a93cc98a5edb5beb2465e2ce6595d8a815e92502ed66b314f9853590fe24c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:3f875d545ec90a35:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "c78702ffc2e3f412f523bee44ba378136ec9d361d538c1711005bfd165bacd22",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:808be1dd0802b41f:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "47b0d54a4b6f6763deb4ef565dc977f8fa404a574b064631f7e7ad93c15b0bcc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:71f7359381e9c85a:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "bb84ad501fce4d09c6f5ce406d0afe148aa7c8f3edb6e0809304eb549e11c871",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:328da672cf537f47:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "2d490bf440db62bc5b2ff8153b9e4866abc27e05ea8e514b72a819bc61a967db",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "used:cc:f2dbe51ddf429de6:6585eac08d8bed73:059a274af5b4dd01",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253",
      "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
      "pid": 12982,
      "sha256": "d8ba05431cccf258e5dc8aca11279a7038deed1ae36828c3efa3f6365cb14165",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "cargo_pkg_name": "slab",
      "cargo_pkg_version": "0.4.9",
      "context_path": "/tmp/native-trace-10402-1783992621011/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-10402-1783992621011/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 12982,
      "ppid": 12942,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
        "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
        "/target/debug/build/slab-b0fe9ec70d8d0253",
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
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/rustcY3r5df/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.1euo5wj.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/slab-b0fe9ec70d8d0253",
          "kind": "object",
          "path": "/target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.1euo5wj.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-12982-1783992626178609391.map",
      "pid": 12982,
      "ppid": 12942,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-12982-1783992626178609391.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
      "parsed_event_count": 323,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 325,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " cc               13043  13038    0 /usr/bin/cc -m64 /target/debug/build/slab-b0fe9ec70d8d0253/rustcPBT2ox/symbols.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.1ndk943eqpxecu7bx125kx46n.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.5xpvvkuetvzxy7pz0djeum7m4.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.7uae0fod748xtniv6z1lhc26x.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.82kbnloy6y955qbnhzxk5ogrs.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.a792tyg0ib6w980zs9qhpw01j.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.ae162jfvcoinxryceozz1guvi.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.d8i4sqgqovkge2jlml7m3za8i.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.f04pt7527fst47vqvvh02ks0g.0tlsyhv.rcgu.o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253.cvkiq4vc5rzd0a6rywxwkak51.0tlsyhv.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd ...\n0.969   ld.lld           13047  13046    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch2JrLs.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/slab-b0fe9ec70d8d0253/build_script_build-b0fe9ec70d8d0253 ...\n0.969   collect2         13046  13043    0 \n0.972   rust-lld         13047  13046    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cch2JrLs.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.972   build-script-bu  13050  12397    0 /target/debug/build/slab-b0fe9ec70d8d0253/build-script-build\n0.980   rustc            13051  13050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n0.989   rustc            13042  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.007   rustc            13057  13050    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_99eb19510c85dce3_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.007   rustc            13058  11664    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.050   rustc            13086  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.096   build-script-bu  13106  12561    0 /target/debug/build/slab-b0fe9ec70d8d0253/build-script-build\n1.106   rustc            13107  13106    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.135   rustc            13115  13106    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_4d8483437660ffb9_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/slab-eed7e102b86e9d2e/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.151   rustc            13124  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.159   rustc            13127  12397    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name slab --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.173   rustc            13131  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.192   rustc            13148  12561    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name slab --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.207   rustc            13150  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.222   rustc            13157  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.322   rustc            13182  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.338   rustc            13188  11664    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.434   rustc            13218  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.489   rustc            13229  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error_attr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-error-attr-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n1.500   rustc            13235  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.547   cc               13262  13182    0 /tmp/native-trace-9934-1783992620245/shims/cc -Wl,--version-script=/target/debug/deps/rustcavC97H/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcavC97H/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcavC97H/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.551   cc               13267  13262    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcavC97H/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcavC97H/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcavC97H/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.557   collect2         13269  13267    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcavC97H/raw-dylibs ...\n1.561   ld.lld           13272  13269    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcavC97H/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.565   rust-lld         13272  13269    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchMEy9l.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n1.615   cc               13331  13188    0 /tmp/native-trace-10036-1783992620315/shims/cc -Wl,--version-script=/target/debug/deps/rustc2O83Gi/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2O83Gi/symbols.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.00x7z5m9oth5mjy0rvnxr7mrk.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.077ownqvpcueidq6jwb55l19w.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0mz6z2561mf68mxslwr4yfxa9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0znw58n8y6gyn9kv52mja79uu.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1hybit02s0bu4qbn6t4vwxtc2.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1i3ntvwuybjtx26mp4jzeyxyy.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1r9dchyq59cmfyvc2gonlfans.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1s7914rt9ctukziehp9m2g0sp.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1sobdcokrw17f9gyf59dqz2fo.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.29zsxjys3de1e9hctxkawbl1a.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.2hjxzvod7juaix7opuypy1nl9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.305qzos0klqsaom3coq1iaeyn.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.32utzn2a3qoad6o5vgfv6h6n8.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3aq1ptjs71fqwi296i98zrpwi.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3brsl01o3jk7obk5yy0bher2x.1ef9ixn.rcgu.o ...\n1.617   cc               13332  13331    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc2O83Gi/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2O83Gi/symbols.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.00x7z5m9oth5mjy0rvnxr7mrk.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.077ownqvpcueidq6jwb55l19w.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0mz6z2561mf68mxslwr4yfxa9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.0znw58n8y6gyn9kv52mja79uu.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1hybit02s0bu4qbn6t4vwxtc2.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1i3ntvwuybjtx26mp4jzeyxyy.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1r9dchyq59cmfyvc2gonlfans.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1s7914rt9ctukziehp9m2g0sp.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.1sobdcokrw17f9gyf59dqz2fo.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.29zsxjys3de1e9hctxkawbl1a.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.2hjxzvod7juaix7opuypy1nl9.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.305qzos0klqsaom3coq1iaeyn.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.32utzn2a3qoad6o5vgfv6h6n8.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3aq1ptjs71fqwi296i98zrpwi.1ef9ixn.rcgu.o /target/debug/deps/proc_macro_error_attr-550cb56dd8294dec.3brsl01o3jk7obk5yy0bher2x.1ef9ixn.rcgu.o ...\n1.622   collect2         13333  13332    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc2O83Gi/raw-dylibs ...\n1.627   ld.lld           13334  13333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc2O83Gi/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.631   rust-lld         13334  13333    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLrnTHI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-550cb56dd8294dec.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n1.694   cc               13353  13229    0 /tmp/native-trace-9930-1783992620242/shims/cc -Wl,--version-script=/target/debug/deps/rustcdcBLIP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcdcBLIP/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcdcBLIP/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.696   cc               13354  13353    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcdcBLIP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcdcBLIP/symbols.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.0.rcgu.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.proc_macro_error_attr.fd877e7a68c8b137-cgu.1.rcgu.o /target/debug/deps/rustcdcBLIP/rmeta.o /target/debug/deps/proc_macro_error_attr-a89ff3dbf6f4bf7e.cnfjapeaqixd5rdc8vhczjele.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.701   collect2         13355  13354    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcdcBLIP/raw-dylibs ...\n1.705   ld.lld           13356  13355    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcdcBLIP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n1.705   rust-lld         13356  13355    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccgATtOB.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libproc_macro_error_attr-a89ff3dbf6f4bf7e.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n1.886   rustc            13384  10577    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.213   rustc            13468  10679    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n2.402   rustc            13480  11517    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.625   rustc            13546  11609    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_error --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"syn\" --cfg feature=\"syn-error\" ...\n2.962   sh               13655  2147557   0 /bin/sh -c which ps\n2.962   rustc            13649  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n2.963   which            13655  2147557   0 /usr/bin/which ps\n2.967   sh               13660  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.970   ps               13660  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.014   sh               13687  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.016   cpuUsage.sh      13687  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n3.018   sed              13688  13687    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.021   cat              13689  13687    0 /usr/bin/cat /proc/2240539/stat\n3.026   cat              13693  13687    0 /usr/bin/cat /proc/4193716/stat\n3.030   sleep            13694  13687    0 /usr/bin/sleep 1\n3.108   cc               13702  13468    0 /tmp/native-trace-9202-1783992619475/shims/cc -Wl,--version-script=/target/debug/deps/rustcZBdSft/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZBdSft/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.109   cc               13703  13702    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcZBdSft/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcZBdSft/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.114   collect2         13706  13703    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZBdSft/raw-dylibs ...\n3.117   ld.lld           13707  13706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcZBdSft/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.121   rust-lld         13707  13706    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchqVn0k.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n3.191   rustc            13726  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n3.244   rustc            13731  10679    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=43084314ea826c64 ...\n3.549   cc               13762  13649    0 /tmp/native-trace-10275-1783992620622/shims/cc -Wl,--version-script=/target/debug/deps/rustcfJWUsc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcfJWUsc/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.550   cc               13763  13762    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcfJWUsc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcfJWUsc/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.555   collect2         13765  13763    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcfJWUsc/raw-dylibs ...\n3.556   ld.lld           13766  13765    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcfJWUsc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.559   rust-lld         13766  13765    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccLy6fiU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n3.673   rustc            13795  11602    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4b8c2419948abb6e ...\n3.692   cc               13799  13726    0 /tmp/native-trace-10179-1783992620472/shims/cc -Wl,--version-script=/target/debug/deps/rustccSz3Dg/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccSz3Dg/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.693   cc               13800  13799    0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustccSz3Dg/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccSz3Dg/symbols.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-d50d5db31b3453fa.thiserror_impl.98cf6ac9d10fe90f-cgu.14.rcgu.o ...\n3.696   collect2         13801  13800    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustccSz3Dg/raw-dylibs ...\n3.697   ld.lld           13802  13801    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustccSz3Dg/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n3.699   rust-lld         13802  13801    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXPdiUc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-d50d5db31b3453fa.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n3.803   rustc            13824  11828    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5a367b47b03d5dda ...\n3.963   runc             13831  4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2511411117 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n3.969   exe              13838  13831    0 /proc/self/exe init\n3.980   curl             13841  13831    0 /usr/bin/curl -f http://localhost:9091/healthz\n4.032   sed              13848  13687    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.035   cat              13849  13687    0 /usr/bin/cat /proc/2240539/stat\n4.036   cat              13851  13687    0 /usr/bin/cat /proc/4193716/stat\n8.802   16               13853  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n8.819   frpc             13853  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.923  runc             13860  3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process1247028754 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n10.930  exe              13867  13860    0 /proc/self/exe init\n10.960  curl             13870  13860    0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.598  16               13877  1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n15.601  16               13878  1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n15.772  systemd-coredum  13877  1        0 /usr/lib/systemd/systemd-coredump\n15.774  drkonqi-coredum  13878  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 882-13876-0\n15.786  runc             13880  9210     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 --log-format json --systemd-cgroup kill --all ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208 9\n15.806  runc             13887  9210     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 --log-format json --systemd-cgroup delete ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208\n15.863  runc             13894  9395     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f --log-format json --systemd-cgroup kill --all cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11 9\n15.872  runc             13900  9395     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f --log-format json --systemd-cgroup delete cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11\n16.051  containerd-shim  13914  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14 delete\n16.054  runc             13921  13914    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa20 --log-format json delete --force ff5b02fcd7f03ac0c9ae872bdcd3cfa19db9a05bf1164d219d8e9b6cc14fa208\n16.063  runc             13926  9510     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 --log-format json --systemd-cgroup kill --all d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301 9\n16.070  runc             13932  9510     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 --log-format json --systemd-cgroup delete d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301\n16.074  runc             13939  9469     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529d --log-format json --systemd-cgroup kill --all fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c 9\n16.082  runc             13945  9469     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529d --log-format json --systemd-cgroup delete fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c\n16.102  sh               13954  13951    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth1b7014c\n16.105  ethtool          13955  13954    0 /usr/sbin/ethtool -i veth1b7014c\n16.105  sed              13956  13954    0 /usr/bin/sed -n s/^driver: //p\n16.107  containerd-shim  13958  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f delete\n16.110  runc             13965  13958    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a1 --log-format json delete --force cf2d5f88977ebd5ff1791ab4625138c71296b54fcf0dc7f889ec618e18f31a11\n16.121  systemd-sysctl   13971  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1b7014c --prefix=/net/ipv4/neigh/veth1b7014c --prefix=/net/ipv6/conf/veth1b7014c --prefix=/net/ipv6/neigh/veth1b7014c\n16.145  systemd-sysctl   13973  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha071b75 --prefix=/net/ipv4/neigh/vetha071b75 --prefix=/net/ipv6/conf/vetha071b75 --prefix=/net/ipv6/neigh/vetha071b75\n16.182  systemd-userwor  13975  50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n16.190  abrt-server      13976  1118     0 /usr/bin/abrt-server -s\n16.192  9                13977  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n16.206  systemd-userwor  13978  50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n16.207  drkonqi-coredum  13977  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n16.220  abrt-handle-eve  13979  13976    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:30:41.527742-7022\n16.236  sh               13980  13979    0 /bin/sh -c abrt-action-save-package-data\\n\n16.238  abrt-action-sav  13980  13979    0 /usr/bin/abrt-action-save-package-data\n16.296  containerd-shim  13986  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51 delete\n16.299  runc             13992  13986    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f730 --log-format json delete --force d06cc67dbc266735a55e07ab60d9e47911a08bdf3d0d1f9c5de4623fb51f7301\n16.301  sh               13998  13979    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n16.303  cut              14000  13998    0 /usr/bin/cut -d: -f1\n16.303  cat              14001  13999    0 /usr/bin/cat uid\n16.304  getent           13999  13998    0 /usr/bin/getent passwd 1000\n16.306  lscpu            14002  13998    0 /usr/bin/lscpu\n16.324  sh               14003  13979    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n16.326  containerd-shim  14005  1663     0 \n16.326  runlevel         14004  14003    0 /usr/bin/runlevel\n16.329  runc             14012  14005    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5 --log-format json delete --force fb5be593ea86a95196e9e62a641d3b26e13b1cdaed81087c1840233529dc5b5c\n16.336  systemd-sysctl   14017  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth45e7814 --prefix=/net/ipv4/neigh/veth45e7814 --prefix=/net/ipv6/conf/veth45e7814 --prefix=/net/ipv6/neigh/veth45e7814\n16.339  sh               14018  13979    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n16.341  grep             14019  14018    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n16.342  grep             14020  14018    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n16.344  grep             14021  14018    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n16.346  abrt-action-cor  14022  14018    0 /usr/libexec/abrt-action-coredump -x\n16.388  systemd-sysctl   14023  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf64f55b --prefix=/net/ipv4/neigh/vethf64f55b --prefix=/net/ipv6/conf/vethf64f55b --prefix=/net/ipv6/neigh/vethf64f55b\n16.415  abrt-action-gen  14024  14018    0 /usr/bin/abrt-action-generate-core-backtrace\n16.475  abrt-action-ana  14025  14018    0 /usr/bin/abrt-action-analyze-vulnerability\n16.477  sed              14029  14026    0 /usr/bin/sed s/[^0-9]//g\n16.478  grep             14028  14026    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n16.478  eu-readelf       14027  14026    0 /usr/bin/eu-readelf -n coredump\n16.480  gdb              14031  14030    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n16.498  iconv            14032  14031    0 /usr/bin/iconv -l\n16.597  abrt-action-ana  14041  14018    0 /usr/bin/abrt-action-analyze-c\n16.611  eu-unstrip       14042  14041    0 /usr/bin/eu-unstrip --core=./coredump -n\n16.632  abrt-action-lis  14043  14018    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n16.696  cat              14045  14044    0 /usr/bin/cat executable\n16.698  cat              14046  14044    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:30:41.527742-7022/uid\n16.700  journalctl       14047  14044    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n16.713  abrt-action-cor  14048  14018    0 /usr/libexec/abrt-action-coredump -r\n16.772  sh               14049  2147557   0 /bin/sh -c which ps\n16.773  which            14049  2147557   0 /usr/bin/which ps\n16.776  abrt-handle-eve  14051  13976    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.776  sh               14050  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.777  ps               14050  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.794  sh               14052  14051    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n16.795  dbus-send        14052  14051    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.797  sh               14053  14051    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n16.798  abrt-action-not  14054  14053    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n16.805  sh               14055  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.807  cpuUsage.sh      14055  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.809  sed              14056  14055    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.810  cat              14057  14055    0 /usr/bin/cat /proc/2240539/stat\n16.811  cat              14058  14055    0 /usr/bin/cat /proc/4193716/stat\n16.812  sleep            14059  14055    0 /usr/bin/sleep 1\n16.850  sh               14060  14054    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n16.851  reporter-system  14060  14054    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.295  runc             14063  9937     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 --log-format json --systemd-cgroup kill --all cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b 9\n17.303  runc             14069  9937     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 --log-format json --systemd-cgroup delete cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b\n17.465  runc             14075  9028     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 --log-format json --systemd-cgroup kill --all f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e 9\n17.479  containerd-shim  14081  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891 delete\n17.482  runc             14087  14081    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36 --log-format json delete --force cd416d507a1635a33e16653c86550acf84578146ef99f6e797525242891ec36b\n17.484  runc             14093  9028     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 --log-format json --systemd-cgroup delete f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e\n17.542  systemd-sysctl   14099  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0d7e1a1 --prefix=/net/ipv4/neigh/veth0d7e1a1 --prefix=/net/ipv6/conf/veth0d7e1a1 --prefix=/net/ipv6/neigh/veth0d7e1a1\n17.607  runc             14101  9281     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c --log-format json --systemd-cgroup kill --all 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780 9\n17.616  runc             14107  9281     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c --log-format json --systemd-cgroup delete 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780\n17.700  containerd-shim  14113  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c7334 delete\n17.703  runc             14120  14113    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092 --log-format json delete --force f252c824fddf02c9f78b67e5ee8dd781493e6edb41b6a88849a0f6c73349092e\n17.744  systemd-sysctl   14126  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethedfce10 --prefix=/net/ipv4/neigh/vethedfce10 --prefix=/net/ipv6/conf/vethedfce10 --prefix=/net/ipv6/neigh/vethedfce10\n17.814  sed              14128  14055    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.816  cat              14129  14055    0 /usr/bin/cat /proc/2240539/stat\n17.818  cat              14131  14055    0 /usr/bin/cat /proc/4193716/stat\n17.827  containerd-shim  14133  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c delete\n17.831  runc             14140  14133    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c5378 --log-format json delete --force 7ebd918b51ad8471367168c2b2f8a7b11de0c2e965e313b425ed5f0651c53780\n17.874  systemd-sysctl   14145  13951    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6402a8f --prefix=/net/ipv4/neigh/veth6402a8f --prefix=/net/ipv6/conf/veth6402a8f --prefix=/net/ipv6/neigh/veth6402a8f\n"
    },
    {
      "argv": [
        "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 13050,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
      "pid": 13050,
      "ppid": 12397,
      "root_cargo_pid": 12397,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 13050,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 13051,
      "ppid": 13050,
      "root_cargo_pid": 12397,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_99eb19510c85dce3_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 13050,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 13057,
      "ppid": 13050,
      "root_cargo_pid": 12397,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "slab",
      "cwd": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "event_id": "bsrun:93e3fdab3db3da61:66f198e27447f3ac:8b19fa83fcf83981",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/slab-b0fe9ec70d8d0253/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
      "out_dir": "/target/debug/build/slab-b0fe9ec70d8d0253/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
      "success": true,
      "target": null,
      "version": "0.4.9",
      "_owner": {
        "crate": "slab",
        "version": "0.4.9",
        "package_id": "path+file:///tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9#slab@0.4.9",
        "manifest_dir": "/tmp/crate-build-riscv64-uj_p33uq/src/slab-0.4.9",
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
      "build_script_root_pid": 13050,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 13051,
      "ppid": 13050,
      "root_cargo_pid": 12397,
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
        "autocfg_99eb19510c85dce3_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/slab-4c98690f33cab2d2/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 13050,
      "build_script_target_dir": "slab-b0fe9ec70d8d0253",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 13057,
      "ppid": 13050,
      "root_cargo_pid": 12397,
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
