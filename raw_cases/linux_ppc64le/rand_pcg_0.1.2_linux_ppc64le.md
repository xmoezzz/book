# `rand_pcg` `0.1.2`

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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
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
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-130917-1783993028722139551.map",
  "pid": 130917,
  "ppid": 130785,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-130917-1783993028722139551.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "workspace_root": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@0.1.8",
      "name": "autocfg",
      "version": "0.1.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
      "name": "bincode",
      "version": "1.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
      "name": "rand_core",
      "version": "0.4.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
      "name": "rand_pcg",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2"
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
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 130917,
  "ppid": 130785,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:ffb2302a59d39390:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
  "pid": 130917,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:0d04e77393cf62cd:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "59bfe9aadbd41f02039c630fc74c051b6109fb983686cba604c2a42c80653c4f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:6f2fc2855a9a34e7:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "30071a37dd0dfcab9b165ae30ca889fc98e5766286ecbe2b095927164dcfb982",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:4f2de9f96af4f6eb:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "ab7d1194372924106ff892845cd178a65a1a2d48dfb4d08e58c3b394d3156b16",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:24b1388251735050:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "e21dc247e3c12a87f22cd76b10d124b465e354f63af22dc6585b0d40fce9e934",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:25801c02cd5d93a8:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "2f2d2842d148c0af647e279a2699e7b2b5d4a03f43ffcabeeb8da7f772f900c4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:650e7711e5ff5bdf:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "ecfe5800792dee608979d400a688adfbb7e9b304fbec687c51a5efeb5af821ac",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "used:cc:9f551c46350ec3de:b7bb7125a6d3adbf:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
  "pid": 130917,
  "sha256": "353fcb1e540a9e3df7013cb0b755e5508f9a3c74e9434db8747e87f445a2c9a2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
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
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-129519-1783993023824/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-129519-1783993023824/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 130917,
  "ppid": 130785,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-130917-1783993028722139551.map",
  "pid": 130917,
  "ppid": 130785,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-130917-1783993028722139551.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
  "parsed_event_count": 1095,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1097,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.046  ld.lld           136589 136584   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prometheus-ebb6dd171d351f72/build_script_build-ebb6dd171d351f72 ...\n16.055  rust-lld         136589 136584   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.091  cc               136607 136494   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/parking_lot_core-460b776de2ff709a/rustci7SYfV/symbols.o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.build_script_build.26c33c2f37b73d75-cg /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.dgphdpnsvr4foy0u0r8ng831g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n16.102  cc               136612 136607   0 /usr/bin/cc -m64 /target/debug/build/parking_lot_core-460b776de2ff709a/rustci7SYfV/symbols.o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.build_script_build.26c33c2f37b73d75-cg /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.dgphdpnsvr4foy0u0r8ng831g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n16.106  sed              136628 136048   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.107  rustc            136614 135985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.111  cat              136633 136048   0 /usr/bin/cat /proc/2240539/stat\n16.115  cat              136636 136048   0 /usr/bin/cat /proc/4193716/stat\n16.139  16               136648 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.155  frpc             136648 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.164  cc               136655 136488   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/proc-macro2-348557bb47e039b1/rustc4zVEyf/symbols.o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.0.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.1.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.ek806yx5ty7mane54y92uv2ed.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.173  cc               136672 136655   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-348557bb47e039b1/rustc4zVEyf/symbols.o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.0.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.1.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.ek806yx5ty7mane54y92uv2ed.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.181  cc               136677 136614   0 /tmp/native-trace-135571-1783993040482/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustciorBWI/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1ntwawd.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.183  collect2         136680 136672   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.183  cc               136682 136677   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustciorBWI/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1ntwawd.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.187  rustc            136673 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=abffc463d93ac1f9 ...\n16.188  ld.lld           136684 136680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1 ...\n16.189  collect2         136683 136682   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.191  ld.lld           136687 136683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.195  rust-lld         136687 136683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.198  rust-lld         136684 136680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.199  build-script-bu  136688 136455   0 /target/debug/build/prometheus-ebb6dd171d351f72/build-script-build\n16.210  collect2         136689 136612   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.215  ld.lld           136694 136689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a ...\n16.218  rust-lld         136694 136689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.242  cc               136729 136491   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/libc-0fe80f2cd7e2bffe/rustcOimr4I/symbols.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.0.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.1.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.2.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.dtxm24gokbq1qpj4e199l0vg8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.244  cc               136739 136729   0 /usr/bin/cc -m64 /target/debug/build/libc-0fe80f2cd7e2bffe/rustcOimr4I/symbols.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.0.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.1.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.2.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.dtxm24gokbq1qpj4e199l0vg8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.250  cc               136740 136510   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/thiserror-9e15f666d5559c64/rustcjasFhq/symbols.o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.0.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.1.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.8a4156lhtz76cl2ogun8bd10l.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.252  collect2         136749 136739   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.256  cc               136751 136740   0 /usr/bin/cc -m64 /target/debug/build/thiserror-9e15f666d5559c64/rustcjasFhq/symbols.o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.0.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.1.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.8a4156lhtz76cl2ogun8bd10l.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.258  ld.lld           136752 136749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe ...\n16.260  collect2         136753 136751   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.264  ld.lld           136754 136753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64 ...\n16.266  rust-lld         136752 136749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.269  rust-lld         136754 136753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.287  rustc            136758 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.317  build-script-bu  136799 136455   0 /target/debug/build/parking_lot_core-460b776de2ff709a/build-script-build\n16.323  build-script-bu  136801 136455   0 /target/debug/build/proc-macro2-348557bb47e039b1/build-script-build\n16.327  cc               136802 136516   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/protobuf-54b9315e68325c93/rustcOXlg9f/symbols.o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.0.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.1.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.2.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.7b1fkoc6ppbymwfk6k4zg0nod.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.329  cc               136803 136802   0 /usr/bin/cc -m64 /target/debug/build/protobuf-54b9315e68325c93/rustcOXlg9f/symbols.o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.0.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.1.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.2.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.7b1fkoc6ppbymwfk6k4zg0nod.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.332  collect2         136805 136803   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.333  rustc            136804 136801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.337  ld.lld           136807 136805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93 ...\n16.341  rust-lld         136807 136805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.359  build-script-bu  136828 135985   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n16.362  rustc            136826 136801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-ebc7363a0d9e6666/out build/probe.rs --target x86_64-unknown-linux-gnu\n16.365  powerpc64le-lin  136829 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/8810994660504513755detect_compiler_family\n16.369  cc1              136830 136829   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/8810994660504513755detect_compiler_family -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.376  build-script-bu  136832 136455   0 /target/debug/build/libc-0fe80f2cd7e2bffe/build-script-build\n16.378  powerpc64le-lin  136837 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n16.386  rustc            136838 136832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.387  powerpc64le-lin  136839 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o -c src/errno.c\n16.392  cc1              136841 136839   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/errno.c -msecure-plt -quiet -dumpbase errno.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n16.403  build-script-bu  136847 136455   0 /target/debug/build/thiserror-9e15f666d5559c64/build-script-build\n16.408  rustc            136852 136847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-49c91b4612a6529f/out build/probe.rs --target riscv64gc-unknown-linux-gnu\n16.410  rustc            136850 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.81/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.411  rustc            136849 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.412  as               136853 136839   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o /tmp/ccGHbWUh.s\n16.421  powerpc64le-lin  136856 136828   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/liberrno.a /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o\n16.426  powerpc64le-lin  136863 136828   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/liberrno.a\n16.433  rustc            136865 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.154/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n16.438  rustc            136870 135985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=22c6847bf8e0dc68 ...\n16.446  build-script-bu  136873 136455   0 /target/debug/build/protobuf-54b9315e68325c93/build-script-build\n16.451  rustc            136877 136873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.471  rustc            136883 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.472  rustc            136888 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name protobuf --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/protobuf-2.28.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\")) -C metadata=d68eb2c0b6ba0b52 ...\n16.514  cc               136900 136883   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcUms6lI/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.517  cc               136901 136900   0 /usr/bin/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcUms6lI/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.521  collect2         136903 136901   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.524  ld.lld           136904 136903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f ...\n16.527  rust-lld         136904 136903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.590  build-script-bu  136926 136455   0 /target/debug/build/lock_api-abdc83643458130f/build-script-build\n16.593  rustc            136927 136926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n16.609  rustc            136931 136926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-c3deeb9e2f5f005a/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n16.636  rustc            136941 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.759  rustc            136955 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.804  rustc            136970 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=9c05807e0281a946 ...\n16.899  rustc            136993 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.916  rustc            136999 136274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.923  rustc            137003 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.961  cc               137022 136999   0 /tmp/native-trace-135773-1783993040646/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.962  cc               137023 137022   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.965  collect2         137024 137023   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.967  ld.lld           137025 137024   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.969  rust-lld         137025 137024   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.045  build-script-bu  137043 136274   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n17.048  riscv64-linux-g  137044 137043   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family.\n17.050  cc1              137045 137044   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family. -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 17123910858420338620detect_compiler_family.c -dumpbase-ext .c\n17.058  riscv64-linux-g  137048 137043   0 /usr/bin/riscv64-linux-gnu-gcc -?\n17.062  riscv64-linux-g  137049 137043   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o -c src/errno.c\n17.064  cc1              137050 137049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/errno.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ -dumpbase ea708c7824d36062-errno.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n17.075  as               137052 137049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o /tmp/ccDdfoDN.s\n17.081  riscv64-linux-g  137054 137043   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o\n17.125  riscv64-linux-g  137056 137043   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a\n17.148  rustc            137058 136274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2d48ebf03200d1bf ...\n17.817  cross            137065 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.819  rustc            137067 137065   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.825  rustc            137067 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.837  rustc            137080 137065   0 /home/xmoe/.cargo/bin/rustc -vV\n17.842  rustc            137080 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.853  cargo            137090 137065   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.858  cargo            137090 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.869  rustc            137099 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.880  rustc            137101 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.892  rustc            137105 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.960  rustc            137111 137065   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.965  rustc            137111 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.977  docker           137125 137065   0 /usr/bin/docker --help\n17.990  docker           137135 137065   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.002  runc             137147 1599     0 /usr/bin/runc --version\n18.006  docker-init      137153 1599     0 /usr/bin/docker-init --version\n18.008  docker           137154 137065   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.021  runc             137165 1599     0 /usr/bin/runc --version\n18.025  docker-init      137171 1599     0 /usr/bin/docker-init --version\n18.047  rustup           137173 137065   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.054  rustup           137182 137065   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.081  rustup           137193 137065   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.110  uname            137202 137065   0 /usr/bin/uname -r\n18.129  docker           137204 137065   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.178  systemd-sysctl   137219 137217   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4766db7 --prefix=/net/ipv4/neigh/veth4766db7 --prefix=/net/ipv6/conf/veth4766db7 --prefix=/net/ipv6/neigh/veth4766db7\n18.180  systemd-sysctl   137220 137218   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2edde8e --prefix=/net/ipv4/neigh/veth2edde8e --prefix=/net/ipv6/conf/veth2edde8e --prefix=/net/ipv6/neigh/veth2edde8e\n18.203  containerd-shim  137254 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 start\n18.210  containerd-shim  137260 137254   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 -address /var/run/docker/containerd/containerd.sock\n18.219  runc             137271 137260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28\n18.228  exe              137279 137271   0 /proc/self/exe init\n18.273  exe              137290 137271   0 /proc/1599/exe -exec-root=/var/run/docker d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 d7da31e8f8e1\n18.308  exe              137300 1599     0 /proc/self/exe /var/run/docker/netns/5fde2a7d6f25 all false\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 130985,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
  "pid": 130985,
  "ppid": 130478,
  "root_cargo_pid": 130478,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out"
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 130985,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 130987,
  "ppid": 130985,
  "root_cargo_pid": 130478,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_0d78465da66d32c7_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 130985,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 130994,
  "ppid": 130985,
  "root_cargo_pid": 130478,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_build_script_out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "rand_pcg",
  "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "event_id": "bsrun:825971ff21310517:5c4fb2aca3f401de:8c840e32d1f630fc",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
  "out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
  "build_script_root_pid": 130985,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 130987,
  "ppid": 130985,
  "root_cargo_pid": 130478,
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
    "autocfg_0d78465da66d32c7_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 130985,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 130994,
  "ppid": 130985,
  "root_cargo_pid": 130478,
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
  "time": "2026-07-14T01:37:26.502341+00:00",
  "crate": "rand_pcg",
  "version": "0.1.2",
  "architecture": "ppc64le",
  "duration_seconds": 29.274422354996204,
  "trace_record_count": 19,
  "trace_owner_summary": {
    "owner_package_count": 12,
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
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "0.1.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@0.1.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "bincode",
        "version": "1.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml"
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
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "manifest_path": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "rand_pcg",
        "version": "0.1.2",
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
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "workspace_root": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@0.1.8",
          "name": "autocfg",
          "version": "0.1.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-0.1.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bincode@1.3.3",
          "name": "bincode",
          "version": "1.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bincode-1.3.3"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
          "name": "rand_core",
          "version": "0.4.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
          "name": "rand_pcg",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2"
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
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 130917,
      "ppid": 130785,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:ffb2302a59d39390:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
      "pid": 130917,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:0d04e77393cf62cd:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "59bfe9aadbd41f02039c630fc74c051b6109fb983686cba604c2a42c80653c4f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:6f2fc2855a9a34e7:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "30071a37dd0dfcab9b165ae30ca889fc98e5766286ecbe2b095927164dcfb982",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:4f2de9f96af4f6eb:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "ab7d1194372924106ff892845cd178a65a1a2d48dfb4d08e58c3b394d3156b16",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:24b1388251735050:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "e21dc247e3c12a87f22cd76b10d124b465e354f63af22dc6585b0d40fce9e934",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:25801c02cd5d93a8:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "2f2d2842d148c0af647e279a2699e7b2b5d4a03f43ffcabeeb8da7f772f900c4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:650e7711e5ff5bdf:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "ecfe5800792dee608979d400a688adfbb7e9b304fbec687c51a5efeb5af821ac",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "used:cc:9f551c46350ec3de:b7bb7125a6d3adbf:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
      "pid": 130917,
      "sha256": "353fcb1e540a9e3df7013cb0b755e5508f9a3c74e9434db8747e87f445a2c9a2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
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
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-129519-1783993023824/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-129519-1783993023824/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 130917,
      "ppid": 130785,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-fd5334c415c657e1.rlib",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc8MWWIA/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0llwner.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0llwner.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-130917-1783993028722139551.map",
      "pid": 130917,
      "ppid": 130785,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-130917-1783993028722139551.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
      "parsed_event_count": 1095,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1097,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.046  ld.lld           136589 136584   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/prometheus-ebb6dd171d351f72/build_script_build-ebb6dd171d351f72 ...\n16.055  rust-lld         136589 136584   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX3Orf6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.091  cc               136607 136494   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/parking_lot_core-460b776de2ff709a/rustci7SYfV/symbols.o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.build_script_build.26c33c2f37b73d75-cg /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.dgphdpnsvr4foy0u0r8ng831g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n16.102  cc               136612 136607   0 /usr/bin/cc -m64 /target/debug/build/parking_lot_core-460b776de2ff709a/rustci7SYfV/symbols.o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.build_script_build.26c33c2f37b73d75-cg /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a.dgphdpnsvr4foy0u0r8ng831g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n16.106  sed              136628 136048   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.107  rustc            136614 135985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.111  cat              136633 136048   0 /usr/bin/cat /proc/2240539/stat\n16.115  cat              136636 136048   0 /usr/bin/cat /proc/4193716/stat\n16.139  16               136648 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n16.155  frpc             136648 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.164  cc               136655 136488   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/proc-macro2-348557bb47e039b1/rustc4zVEyf/symbols.o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.0.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.1.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.ek806yx5ty7mane54y92uv2ed.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.173  cc               136672 136655   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-348557bb47e039b1/rustc4zVEyf/symbols.o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.0.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.build_script_build.364e9b7bc1392c2b-cgu.1.r /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1.ek806yx5ty7mane54y92uv2ed.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.181  cc               136677 136614   0 /tmp/native-trace-135571-1783993040482/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustciorBWI/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1ntwawd.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.183  collect2         136680 136672   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.183  cc               136682 136677   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustciorBWI/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1ntwawd.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1ntwawd.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.187  rustc            136673 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=abffc463d93ac1f9 ...\n16.188  ld.lld           136684 136680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-348557bb47e039b1/build_script_build-348557bb47e039b1 ...\n16.189  collect2         136683 136682   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.191  ld.lld           136687 136683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.195  rust-lld         136687 136683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccfpA6is.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.198  rust-lld         136684 136680   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7SsIDE.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.199  build-script-bu  136688 136455   0 /target/debug/build/prometheus-ebb6dd171d351f72/build-script-build\n16.210  collect2         136689 136612   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.215  ld.lld           136694 136689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/parking_lot_core-460b776de2ff709a/build_script_build-460b776de2ff709a ...\n16.218  rust-lld         136694 136689   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccmmLNHP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.242  cc               136729 136491   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/libc-0fe80f2cd7e2bffe/rustcOimr4I/symbols.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.0.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.1.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.2.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.dtxm24gokbq1qpj4e199l0vg8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.244  cc               136739 136729   0 /usr/bin/cc -m64 /target/debug/build/libc-0fe80f2cd7e2bffe/rustcOimr4I/symbols.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.0.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.1.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.build_script_build.ca0af55305537db8-cgu.2.rcgu.o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe.dtxm24gokbq1qpj4e199l0vg8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.250  cc               136740 136510   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/thiserror-9e15f666d5559c64/rustcjasFhq/symbols.o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.0.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.1.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.8a4156lhtz76cl2ogun8bd10l.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.252  collect2         136749 136739   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.256  cc               136751 136740   0 /usr/bin/cc -m64 /target/debug/build/thiserror-9e15f666d5559c64/rustcjasFhq/symbols.o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.0.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.build_script_build.be6c43d112ca696a-cgu.1.rcg /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64.8a4156lhtz76cl2ogun8bd10l.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.258  ld.lld           136752 136749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-0fe80f2cd7e2bffe/build_script_build-0fe80f2cd7e2bffe ...\n16.260  collect2         136753 136751   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.264  ld.lld           136754 136753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/thiserror-9e15f666d5559c64/build_script_build-9e15f666d5559c64 ...\n16.266  rust-lld         136752 136749   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccrbRTPD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.269  rust-lld         136754 136753   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3c3CB6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.287  rustc            136758 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.317  build-script-bu  136799 136455   0 /target/debug/build/parking_lot_core-460b776de2ff709a/build-script-build\n16.323  build-script-bu  136801 136455   0 /target/debug/build/proc-macro2-348557bb47e039b1/build-script-build\n16.327  cc               136802 136516   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/protobuf-54b9315e68325c93/rustcOXlg9f/symbols.o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.0.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.1.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.2.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.7b1fkoc6ppbymwfk6k4zg0nod.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.329  cc               136803 136802   0 /usr/bin/cc -m64 /target/debug/build/protobuf-54b9315e68325c93/rustcOXlg9f/symbols.o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.0.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.1.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.build_script_build.6861d656775dcdcc-cgu.2.rcgu /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93.7b1fkoc6ppbymwfk6k4zg0nod.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al ...\n16.332  collect2         136805 136803   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.333  rustc            136804 136801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.337  ld.lld           136807 136805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/protobuf-54b9315e68325c93/build_script_build-54b9315e68325c93 ...\n16.341  rust-lld         136807 136805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccnhjkyf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.359  build-script-bu  136828 135985   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n16.362  rustc            136826 136801   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-ebc7363a0d9e6666/out build/probe.rs --target x86_64-unknown-linux-gnu\n16.365  powerpc64le-lin  136829 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/8810994660504513755detect_compiler_family\n16.369  cc1              136830 136829   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/8810994660504513755detect_compiler_family -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.376  build-script-bu  136832 136455   0 /target/debug/build/libc-0fe80f2cd7e2bffe/build-script-build\n16.378  powerpc64le-lin  136837 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n16.386  rustc            136838 136832   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.387  powerpc64le-lin  136839 136828   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o -c src/errno.c\n16.392  cc1              136841 136839   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu src/errno.c -msecure-plt -quiet -dumpbase errno.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections ...\n16.403  build-script-bu  136847 136455   0 /target/debug/build/thiserror-9e15f666d5559c64/build-script-build\n16.408  rustc            136852 136847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --edition=2018 --crate-name=thiserror --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/thiserror-49c91b4612a6529f/out build/probe.rs --target riscv64gc-unknown-linux-gnu\n16.410  rustc            136850 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.81/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.411  rustc            136849 136061   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.412  as               136853 136839   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o /tmp/ccGHbWUh.s\n16.421  powerpc64le-lin  136856 136828   0 /usr/bin/powerpc64le-linux-gnu-ar cqD /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/liberrno.a /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/ea708c7824d36062-errno.o\n16.426  powerpc64le-lin  136863 136828   0 /usr/bin/powerpc64le-linux-gnu-ar sD /target/powerpc64le-unknown-linux-gnu/debug/build/errno-dragonfly-acf7daaa52e6a910/out/liberrno.a\n16.433  rustc            136865 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.154/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n16.438  rustc            136870 135985   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=22c6847bf8e0dc68 ...\n16.446  build-script-bu  136873 136455   0 /target/debug/build/protobuf-54b9315e68325c93/build-script-build\n16.451  rustc            136877 136873   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.471  rustc            136883 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.472  rustc            136888 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name protobuf --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/protobuf-2.28.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"bytes\", \"serde\", \"serde_derive\", \"with-bytes\", \"with-serde\")) -C metadata=d68eb2c0b6ba0b52 ...\n16.514  cc               136900 136883   0 /tmp/native-trace-135939-1783993040897/shims/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcUms6lI/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.517  cc               136901 136900   0 /usr/bin/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcUms6lI/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.521  collect2         136903 136901   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.524  ld.lld           136904 136903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f ...\n16.527  rust-lld         136904 136903   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvCqVEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.590  build-script-bu  136926 136455   0 /target/debug/build/lock_api-abdc83643458130f/build-script-build\n16.593  rustc            136927 136926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n16.609  rustc            136931 136926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-c3deeb9e2f5f005a/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n16.636  rustc            136941 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.759  rustc            136955 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.804  rustc            136970 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=9c05807e0281a946 ...\n16.899  rustc            136993 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.916  rustc            136999 136274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.923  rustc            137003 136455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n16.961  cc               137022 136999   0 /tmp/native-trace-135773-1783993040646/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.962  cc               137023 137022   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.965  collect2         137024 137023   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.967  ld.lld           137025 137024   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.969  rust-lld         137025 137024   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccL1DEtD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.045  build-script-bu  137043 136274   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n17.048  riscv64-linux-g  137044 137043   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family.\n17.050  cc1              137045 137044   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family. -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 17123910858420338620detect_compiler_family.c -dumpbase-ext .c\n17.058  riscv64-linux-g  137048 137043   0 /usr/bin/riscv64-linux-gnu-gcc -?\n17.062  riscv64-linux-g  137049 137043   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o -c src/errno.c\n17.064  cc1              137050 137049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu src/errno.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ -dumpbase ea708c7824d36062-errno.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n17.075  as               137052 137049   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o /tmp/ccDdfoDN.s\n17.081  riscv64-linux-g  137054 137043   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o\n17.125  riscv64-linux-g  137056 137043   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a\n17.148  rustc            137058 136274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2d48ebf03200d1bf ...\n17.817  cross            137065 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.819  rustc            137067 137065   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.825  rustc            137067 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.837  rustc            137080 137065   0 /home/xmoe/.cargo/bin/rustc -vV\n17.842  rustc            137080 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.853  cargo            137090 137065   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.858  cargo            137090 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.869  rustc            137099 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.880  rustc            137101 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.892  rustc            137105 137090   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.960  rustc            137111 137065   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.965  rustc            137111 137065   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.977  docker           137125 137065   0 /usr/bin/docker --help\n17.990  docker           137135 137065   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.002  runc             137147 1599     0 /usr/bin/runc --version\n18.006  docker-init      137153 1599     0 /usr/bin/docker-init --version\n18.008  docker           137154 137065   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.021  runc             137165 1599     0 /usr/bin/runc --version\n18.025  docker-init      137171 1599     0 /usr/bin/docker-init --version\n18.047  rustup           137173 137065   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.054  rustup           137182 137065   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.081  rustup           137193 137065   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.110  uname            137202 137065   0 /usr/bin/uname -r\n18.129  docker           137204 137065   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.178  systemd-sysctl   137219 137217   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4766db7 --prefix=/net/ipv4/neigh/veth4766db7 --prefix=/net/ipv6/conf/veth4766db7 --prefix=/net/ipv6/neigh/veth4766db7\n18.180  systemd-sysctl   137220 137218   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2edde8e --prefix=/net/ipv4/neigh/veth2edde8e --prefix=/net/ipv6/conf/veth2edde8e --prefix=/net/ipv6/neigh/veth2edde8e\n18.203  containerd-shim  137254 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 start\n18.210  containerd-shim  137260 137254   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 -address /var/run/docker/containerd/containerd.sock\n18.219  runc             137271 137260   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28\n18.228  exe              137279 137271   0 /proc/self/exe init\n18.273  exe              137290 137271   0 /proc/1599/exe -exec-root=/var/run/docker d54f06e948be9483eb9e9f28a555469cd2bf55c449d5d5ba552e7050eeb03a28 d7da31e8f8e1\n18.308  exe              137300 1599     0 /proc/self/exe /var/run/docker/netns/5fde2a7d6f25 all false\n"
    },
    {
      "argv": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 130985,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
      "pid": 130985,
      "ppid": 130478,
      "root_cargo_pid": 130478,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 130985,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 130987,
      "ppid": 130985,
      "root_cargo_pid": 130478,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_0d78465da66d32c7_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 130985,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 130994,
      "ppid": 130985,
      "root_cargo_pid": 130478,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rand_pcg",
      "cwd": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "event_id": "bsrun:825971ff21310517:5c4fb2aca3f401de:8c840e32d1f630fc",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
      "out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-ppc64le-mz0vgf6t/src/rand_pcg-0.1.2",
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
      "build_script_root_pid": 130985,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 130987,
      "ppid": 130985,
      "root_cargo_pid": 130478,
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
        "autocfg_0d78465da66d32c7_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/rand_pcg-b90b7fc83d452419/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 130985,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 130994,
      "ppid": 130985,
      "root_cargo_pid": 130478,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 659,
    "crate": "rand_pcg",
    "version": "0.1.2",
    "crate_id": "87994",
    "version_id": "135492",
    "downloads": 42638274,
    "cumulative_downloads": 79019387065,
    "cumulative_share_of_global": 0.29543524615101985,
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
