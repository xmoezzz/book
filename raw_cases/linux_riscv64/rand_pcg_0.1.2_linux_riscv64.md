# `rand_pcg` `0.1.2`

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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-129631-1783993024235965814.map",
  "pid": 129631,
  "ppid": 129614,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-129631-1783993024235965814.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "workspace_root": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
      "name": "rand_pcg",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 129631,
  "ppid": 129614,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:6cb9474def642979:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
  "pid": 129631,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:5566f0220dc335ec:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "28e2cf4720a141b0f5487933f1a33f7cbabab37c5e707048a3d88dd4d02e5822",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:a568bf0aa0f093df:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "31833dada63968a18d364787e5222aa6efd22464eefb7f0a6fc3d8a23fb0f38f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:da7111d6273130b2:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "097b709b65d059d7ca9081c41731d0d9f34dbb2d160320d1f84ffc454cc8a959",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:6570ef11249b7689:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "88b134da757499e363a14d8c672c6da55c3d54c42db6267fe02feef5d5e31395",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:13e192cf98a6ceca:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "125b80080cc5fe75e872cde2f3cc2e7561d4571d18f64ba0bd8ed583771bf9ca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:b68550d59bc7f240:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "6fce6f92f366e9f8c5c5b624ddebb160138307004678982272153bfaad835f04",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "used:cc:40d5c39b3ed204a8:5dd260022fbfae71:c74272e40df229cc",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
  "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
  "pid": 129631,
  "sha256": "353fcb1e540a9e3df7013cb0b755e5508f9a3c74e9434db8747e87f445a2c9a2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "cargo_pkg_name": "rand_pcg",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-128117-1783993018969/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-128117-1783993018969/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 129631,
  "ppid": 129614,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
      "kind": "object",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-129631-1783993024235965814.map",
  "pid": 129631,
  "ppid": 129614,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-129631-1783993024235965814.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
  "parsed_event_count": 989,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 991,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.705  cc               134635 134634   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcViOdM6/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.708  collect2         134636 134635   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.710  ld.lld           134637 134636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n15.712  rust-lld         134637 134636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.721  cc               134639 134582   0 /tmp/native-trace-134335-1783993036876/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcfoluAq/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.723  cc               134641 134639   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcfoluAq/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.727  collect2         134658 134641   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.730  ld.lld           134659 134658   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n15.732  rust-lld         134659 134658   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.761  rustc            134686 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.779  build-script-bu  134695 134570   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n15.782  rustc            134698 134695   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.801  build-script-bu  134704 134570   0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n15.804  rustc            134707 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.805  rustc            134706 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"colors\" --cfg feature=\"default\" --cfg feature=\"yansi\" ...\n15.818  rustc            134713 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span.rs --target powerpc64le-unknown-linux-gnu\n15.832  cc               134717 134619   0 /tmp/native-trace-134348-1783993036926/shims/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcEO8N4y/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.833  cc               134724 134717   0 /usr/bin/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcEO8N4y/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.836  collect2         134727 134724   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.838  ld.lld           134728 134727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a ...\n15.839  rust-lld         134728 134727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.842  cc               134729 134706   0 /tmp/native-trace-134335-1783993036876/shims/cc -m64 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustcpn3ZoR/symbols.o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1voyk -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n15.844  cc               134730 134729   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustcpn3ZoR/symbols.o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1voyk -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n15.846  rustc            134731 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_location.rs --target powerpc64le-unknown-linux-gnu\n15.847  collect2         134732 134730   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.848  ld.lld           134733 134732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143 ...\n15.850  rust-lld         134733 134732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.870  rustc            134769 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_file.rs --target powerpc64le-unknown-linux-gnu\n15.883  build-script-bu  134774 134601   0 /target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build\n15.885  rustc            134775 134774   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.895  build-script-bu  134781 134570   0 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build\n15.896  rustc            134778 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.897  rustc            134784 134781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n15.899  rustc            134783 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.102  rustc            134795 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.155  cross            134805 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.157  rustc            134807 134805   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.158  cross            134808 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.161  rustc            134812 134808   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.166  rustc            134807 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.171  rustc            134812 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.175  cross            134830 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.177  rustc            134836 134830   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.183  rustc            134846 134805   0 /home/xmoe/.cargo/bin/rustc -vV\n16.184  rustc            134836 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.188  rustc            134850 134808   0 /home/xmoe/.cargo/bin/rustc -vV\n16.194  rustc            134846 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.194  rustc            134850 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.197  rustc            134870 134830   0 /home/xmoe/.cargo/bin/rustc -vV\n16.203  rustc            134870 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.206  cargo            134881 134805   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.207  cargo            134882 134808   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.212  cargo            134881 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.212  cargo            134882 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.215  cargo            134900 134830   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.222  rustc            134904 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.223  cargo            134900 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.225  rustc            134913 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.225  rustc            134914 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.234  rustc            134920 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.236  rustc            134922 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.237  rustc            134921 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.246  rustc            134931 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.248  rustc            134932 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.248  rustc            134933 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.258  rustc            134943 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.459  rustc            134970 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.470  rustc            134972 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.501  rustc            134975 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.520  rustc            134979 134805   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.521  rustc            134980 134808   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.526  rustc            134979 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.526  rustc            134980 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.528  rustc            134999 134830   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.534  rustc            134999 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.538  docker           135023 134805   0 /usr/bin/docker --help\n16.539  docker           135022 134808   0 /usr/bin/docker --help\n16.542  cc               135024 134975   0 /tmp/native-trace-134348-1783993036926/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcS6MiUq/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1cufun0.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.543  cc               135037 135024   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcS6MiUq/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1cufun0.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.546  collect2         135040 135037   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.547  docker           135047 134830   0 /usr/bin/docker --help\n16.548  ld.lld           135048 135040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.549  rust-lld         135048 135040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.553  docker           135055 134805   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.555  docker           135057 134808   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.560  docker           135072 134830   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.566  runc             135105 1599     0 /usr/bin/runc --version\n16.568  runc             135107 1599     0 /usr/bin/runc --version\n16.570  docker-init      135121 1599     0 /usr/bin/docker-init --version\n16.571  docker-init      135122 1599     0 /usr/bin/docker-init --version\n16.571  docker           135123 134808   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.573  docker           135124 134805   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.576  runc             135135 1599     0 /usr/bin/runc --version\n16.579  docker-init      135143 1599     0 /usr/bin/docker-init --version\n16.580  docker           135145 134830   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.586  runc             135157 1599     0 /usr/bin/runc --version\n16.587  runc             135158 1599     0 /usr/bin/runc --version\n16.590  16               135170 1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n16.591  docker-init      135174 1599     0 /usr/bin/docker-init --version\n16.591  docker-init      135175 1599     0 /usr/bin/docker-init --version\n16.593  16               135176 1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n16.596  runc             135182 1599     0 /usr/bin/runc --version\n16.600  docker-init      135188 1599     0 /usr/bin/docker-init --version\n16.617  rustup           135189 134808   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.621  rustup           135191 134805   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.625  rustup           135207 134808   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.627  rustup           135208 134830   0 \n16.628  rustup           135209 134805   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.633  rustup           135234 134830   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.640  build-script-bu  135244 134601   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n16.643  aarch64-linux-g  135245 135244   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/15304498930840454446detect_compiler_family.c\n16.645  cc1              135246 135245   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/15304498930840454446detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.652  aarch64-linux-g  135247 135244   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.655  rustup           135249 134808   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.656  aarch64-linux-g  135248 135244   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o -c src/errno.c\n16.658  rustup           135250 134805   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.658  cc1              135251 135248   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/errno.c -quiet -dumpbase errno.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n16.662  rustup           135268 134830   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.674  as               135277 135248   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o /tmp/cculmR6Y.s\n16.684  uname            135278 134808   0 /usr/bin/uname -r\n16.686  uname            135279 134805   0 /usr/bin/uname -r\n16.686  aarch64-linux-g  135280 135244   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/liberrno.a /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o\n16.690  aarch64-linux-g  135281 135244   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/liberrno.a\n16.690  uname            135282 134830   0 /usr/bin/uname -r\n16.696  rustc            135284 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=53b2dae70a4a483e ...\n16.705  docker           135286 134808   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.706  docker           135289 134805   0 \n16.711  docker           135300 134830   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.718  systemd-coredum  135170 1        0 /usr/lib/systemd/systemd-coredump\n16.722  drkonqi-coredum  135176 1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 902-135138-0\n16.776  systemd-sysctl   135329 135327   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe7f190c --prefix=/net/ipv4/neigh/vethe7f190c --prefix=/net/ipv6/conf/vethe7f190c --prefix=/net/ipv6/neigh/vethe7f190c\n16.778  systemd-sysctl   135332 135328   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth507313e --prefix=/net/ipv4/neigh/veth507313e --prefix=/net/ipv6/conf/veth507313e --prefix=/net/ipv6/neigh/veth507313e\n16.779  systemd-sysctl   135333 135331   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9babf0c --prefix=/net/ipv4/neigh/veth9babf0c --prefix=/net/ipv6/conf/veth9babf0c --prefix=/net/ipv6/neigh/veth9babf0c\n16.781  systemd-sysctl   135335 135334   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbafc3c1 --prefix=/net/ipv4/neigh/vethbafc3c1 --prefix=/net/ipv6/conf/vethbafc3c1 --prefix=/net/ipv6/neigh/vethbafc3c1\n16.810  cross            135367 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.811  rustc            135370 135367   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.816  rustc            135370 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.827  rustc            135384 135367   0 /home/xmoe/.cargo/bin/rustc -vV\n16.832  rustc            135384 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.834  9                135399 4003047   0 /proc/self/fd/9 --deserialize 30 --log-level info --log-target auto\n16.839  abrt-server      135400 1118     0 /usr/bin/abrt-server -s\n16.842  cargo            135402 135367   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.845  drkonqi-coredum  135399 4003047   0 /usr/libexec/drkonqi-coredump-launcher\n16.847  cargo            135402 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.858  rustc            135411 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.862  abrt-handle-eve  135412 135400   0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:37:20.224570-131780\n16.868  rustc            135414 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.875  sh               135419 135412   0 /bin/sh -c abrt-action-save-package-data\\n\n16.877  abrt-action-sav  135419 135412   0 /usr/bin/abrt-action-save-package-data\n16.880  rustc            135423 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.882  9                135424 4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n16.885  systemd-sysctl   135425 135359   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaf765b1 --prefix=/net/ipv4/neigh/vethaf765b1 --prefix=/net/ipv6/conf/vethaf765b1 --prefix=/net/ipv6/neigh/vethaf765b1\n16.885  systemd-sysctl   135426 135337   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethafd0901 --prefix=/net/ipv4/neigh/vethafd0901 --prefix=/net/ipv6/conf/vethafd0901 --prefix=/net/ipv6/neigh/vethafd0901\n16.888  plasma_waitforn  135424 4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n16.912  containerd-shim  135431 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 start\n16.915  containerd-shim  135438 135431   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 -address /var/run/docker/containerd/containerd.sock\n16.918  runc             135447 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n16.924  exe              135454 135447   0 /proc/self/exe init\n16.934  sh               135456 135412   0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n16.936  cat              135459 135457   0 /usr/bin/cat uid\n16.936  cut              135458 135456   0 /usr/bin/cut -d: -f1\n16.937  getent           135457 135456   0 /usr/bin/getent passwd 1000\n16.938  lscpu            135466 135456   0 /usr/bin/lscpu\n16.951  rustc            135468 135367   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.951  sh               135469 135412   0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n16.953  runlevel         135470 135469   0 /usr/bin/runlevel\n16.954  exe              135476 135447   0 /proc/1599/exe -exec-root=/var/run/docker c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 d7da31e8f8e1\n16.957  rustc            135468 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.963  sh               135486 135412   0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n16.965  grep             135488 135486   0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n16.966  grep             135491 135486   0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n16.968  grep             135492 135486   0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n16.969  docker           135493 135367   0 /usr/bin/docker --help\n16.969  abrt-action-cor  135494 135486   0 /usr/libexec/abrt-action-coredump -x\n16.977  exe              135507 1599     0 /proc/self/exe /var/run/docker/netns/f309c401b495 all false\n16.982  docker           135513 135367   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.994  runc             135534 1599     0 /usr/bin/runc --version\n16.998  docker-init      135540 1599     0 /usr/bin/docker-init --version\n16.999  docker           135541 135367   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.011  runc             135552 1599     0 /usr/bin/runc --version\n17.015  docker-init      135558 1599     0 /usr/bin/docker-init --version\n17.026  abrt-action-gen  135559 135486   0 /usr/bin/abrt-action-generate-core-backtrace\n17.064  runc             135565 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup start c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n17.070  sh               135461 135438   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.071  cargo            135571 135461   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.071  abrt-action-ana  135572 135486   0 /usr/bin/abrt-action-analyze-vulnerability\n17.073  containerd-shim  135573 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f start\n17.074  eu-readelf       135575 135574   0 /usr/bin/eu-readelf -n coredump\n17.076  containerd-shim  135581 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3 start\n17.076  grep             135576 135574   0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n17.077  sed              135577 135574   0 /usr/bin/sed s/[^0-9]//g\n17.078  containerd-shim  135587 135573   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f -address /var/run/docker/containerd/containerd.sock\n17.080  containerd-shim  135595 135581   0 \n17.081  gdb              135598 135596   0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n17.083  runc             135606 135587   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f\n17.086  runc             135618 135595   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3\n17.088  cargo-native-tr  135571 135461   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.088  rustup           135619 135367   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.090  exe              135635 135606   0 /proc/self/exe init\n17.092  cargo            135636 135571   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.093  exe              135639 135618   0 /proc/self/exe init\n17.095  rustup           135643 135367   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.100  iconv            135652 135598   0 /usr/bin/iconv -l\n17.105  rustc            135653 135636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.117  rustc            135677 135636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.123  rustup           135678 135367   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.130  exe              135690 135606   0 /proc/1599/exe -exec-root=/var/run/docker fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f d7da31e8f8e1\n17.132  exe              135691 135618   0 /proc/1599/exe -exec-root=/var/run/docker d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3 d7da31e8f8e1\n17.136  execsnoop        135702 135571   0 /usr/local/bin/execsnoop -t\n17.137  python3          135702 135571   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.150  uname            135707 135367   0 /usr/bin/uname -r\n17.155  exe              135709 1599     0 /proc/self/exe /var/run/docker/netns/fa5d3e6db347 all false\n17.156  exe              135710 1599     0 /proc/self/exe /var/run/docker/netns/e66f314cd096 all false\n17.170  docker           135738 135367   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.187  abrt-action-ana  135753 135486   0 /usr/bin/abrt-action-analyze-c\n17.197  eu-unstrip       135754 135753   0 /usr/bin/eu-unstrip --core=./coredump -n\n17.212  rustc            135758 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2_diagnostics --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"colors\" --cfg feature=\"default\" --cfg feature=\"yansi\" ...\n17.213  abrt-action-lis  135759 135486   0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n17.220  systemd-sysctl   135760 135337   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth317a84f --prefix=/net/ipv4/neigh/veth317a84f --prefix=/net/ipv6/conf/veth317a84f --prefix=/net/ipv6/neigh/veth317a84f\n17.221  systemd-sysctl   135761 135359   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4d6bdd7 --prefix=/net/ipv4/neigh/veth4d6bdd7 --prefix=/net/ipv6/conf/veth4d6bdd7 --prefix=/net/ipv6/neigh/veth4d6bdd7\n17.226  runc             135766 135587   0 \n17.234  sh               135663 135587   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.236  cargo            135773 135663   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.238  runc             135774 135595   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --log-format json --systemd-cgroup start d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3\n17.245  sh               135670 135595   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.247  cargo            135780 135670   0 \n17.251  cargo-native-tr  135773 135663   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.256  cargo            135781 135773   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.260  cargo-native-tr  135780 135670   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.265  cargo            135783 135780   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.270  rustc            135784 135781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.278  rustc            135785 135783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.279  cat              135788 135787   0 /usr/bin/cat executable\n17.280  cat              135789 135787   0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:37:20.224570-131780/uid\n17.282  journalctl       135791 135787   0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n17.284  rustc            135790 135781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.294  rustc            135794 135783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.295  containerd-shim  135797 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 start\n17.298  abrt-action-cor  135802 135486   0 /usr/libexec/abrt-action-coredump -r\n17.300  containerd-shim  135805 135797   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 -address /var/run/docker/containerd/containerd.sock\n17.305  runc             135818 135805   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009\n17.310  execsnoop        135825 135773   0 /usr/local/bin/execsnoop -t\n17.310  python3          135825 135773   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.314  exe              135829 135818   0 /proc/self/exe init\n17.361  exe              135841 135818   0 /proc/1599/exe -exec-root=/var/run/docker 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 d7da31e8f8e1\n17.372  abrt-handle-eve  135849 135400   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.386  sh               135857 135849   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n17.390  dbus-send        135857 135849   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.396  sh               135865 135849   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n17.399  abrt-action-not  135868 135865   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.401  exe              135869 1599     0 /proc/self/exe /var/run/docker/netns/bce91fa060ac all false\n17.472  execsnoop        135929 135780   0 /usr/local/bin/execsnoop -t\n17.474  runc             135931 135805   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --log-format json --systemd-cgroup start 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009\n17.474  python3          135929 135780   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.481  sh               135834 135805   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.483  cargo            135939 135834   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.492  sh               135941 135868   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n17.493  reporter-system  135941 135868   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.501  cargo-native-tr  135939 135834   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.507  cargo            135943 135939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.524  rustc            135947 135943   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.538  rustc            135949 135943   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.653  execsnoop        135956 135939   0 /usr/local/bin/execsnoop -t\n17.655  python3          135956 135939   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 129677,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
  "pid": 129677,
  "ppid": 129424,
  "root_cargo_pid": 129424,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
  "build_script_root_pid": 129677,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 129679,
  "ppid": 129677,
  "root_cargo_pid": 129424,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_build_script_out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_7dd9ae61cfa3d8f9_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/rand_pcg-fa4faf33fee0fa1d/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 129677,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 129686,
  "ppid": 129677,
  "root_cargo_pid": 129424,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_build_script_out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "rand_pcg",
  "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "event_id": "bsrun:d4f667fd5c8557bb:5c4fb2aca3f401de:8c840e32d1f630fc",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
  "out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "rand_pcg",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
  "build_script_root_pid": 129677,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 129679,
  "ppid": 129677,
  "root_cargo_pid": 129424,
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
    "autocfg_7dd9ae61cfa3d8f9_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/rand_pcg-fa4faf33fee0fa1d/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 129677,
  "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 129686,
  "ppid": 129677,
  "root_cargo_pid": 129424,
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
  "time": "2026-07-14T01:37:22.120333+00:00",
  "crate": "rand_pcg",
  "version": "0.1.2",
  "architecture": "riscv64",
  "duration_seconds": 28.31091827712953,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "manifest_path": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "workspace_root": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
          "name": "rand_pcg",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 129631,
      "ppid": 129614,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:6cb9474def642979:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
      "pid": 129631,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:5566f0220dc335ec:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "28e2cf4720a141b0f5487933f1a33f7cbabab37c5e707048a3d88dd4d02e5822",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:a568bf0aa0f093df:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "31833dada63968a18d364787e5222aa6efd22464eefb7f0a6fc3d8a23fb0f38f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:da7111d6273130b2:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "097b709b65d059d7ca9081c41731d0d9f34dbb2d160320d1f84ffc454cc8a959",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:6570ef11249b7689:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "88b134da757499e363a14d8c672c6da55c3d54c42db6267fe02feef5d5e31395",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:13e192cf98a6ceca:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "125b80080cc5fe75e872cde2f3cc2e7561d4571d18f64ba0bd8ed583771bf9ca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:b68550d59bc7f240:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "6fce6f92f366e9f8c5c5b624ddebb160138307004678982272153bfaad835f04",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "used:cc:40d5c39b3ed204a8:5dd260022fbfae71:c74272e40df229cc",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5",
      "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
      "pid": 129631,
      "sha256": "353fcb1e540a9e3df7013cb0b755e5508f9a3c74e9434db8747e87f445a2c9a2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "cargo_pkg_name": "rand_pcg",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-128117-1783993018969/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-128117-1783993018969/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 129631,
      "ppid": 129614,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
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
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/rustc9MGzkX/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.8660076hrjxg8vithohkpqe1o.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.9qw6h8om888g34vcu5stmvt6r.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dj2yx6cgglsvbd1ffc1fwggue.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.dnq8gjj83c9tp0dt4cx10wukj.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.ehtjm4uarmrhcc509lj8rev79.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.epx25x9v5mooclfbb6u3ggq8u.0t80zdt.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rand_pcg-a9cc825a09faf9c5",
          "kind": "object",
          "path": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build_script_build-a9cc825a09faf9c5.288e8zmxw9kper022kujbf19q.0t80zdt.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-129631-1783993024235965814.map",
      "pid": 129631,
      "ppid": 129614,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-129631-1783993024235965814.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
      "parsed_event_count": 989,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 991,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.705  cc               134635 134634   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcViOdM6/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n15.708  collect2         134636 134635   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.710  ld.lld           134637 134636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n15.712  rust-lld         134637 134636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczmRjjD.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.721  cc               134639 134582   0 /tmp/native-trace-134335-1783993036876/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcfoluAq/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.723  cc               134641 134639   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcfoluAq/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n15.727  collect2         134658 134641   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.730  ld.lld           134659 134658   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n15.732  rust-lld         134659 134658   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYVnTh7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.761  rustc            134686 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.779  build-script-bu  134695 134570   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n15.782  rustc            134698 134695   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.801  build-script-bu  134704 134570   0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n15.804  rustc            134707 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.805  rustc            134706 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"colors\" --cfg feature=\"default\" --cfg feature=\"yansi\" ...\n15.818  rustc            134713 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span.rs --target powerpc64le-unknown-linux-gnu\n15.832  cc               134717 134619   0 /tmp/native-trace-134348-1783993036926/shims/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcEO8N4y/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.833  cc               134724 134717   0 /usr/bin/cc -m64 /target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcEO8N4y/symbols.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.836  collect2         134727 134724   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.838  ld.lld           134728 134727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a ...\n15.839  rust-lld         134728 134727   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWVLmTm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.842  cc               134729 134706   0 /tmp/native-trace-134335-1783993036876/shims/cc -m64 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustcpn3ZoR/symbols.o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1voyk -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n15.844  cc               134730 134729   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustcpn3ZoR/symbols.o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1voyk /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1voyk -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n15.846  rustc            134731 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_location.rs --target powerpc64le-unknown-linux-gnu\n15.847  collect2         134732 134730   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.848  ld.lld           134733 134732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143 ...\n15.850  rust-lld         134733 134732   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccORZmKR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.870  rustc            134769 134704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_file.rs --target powerpc64le-unknown-linux-gnu\n15.883  build-script-bu  134774 134601   0 /target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build\n15.885  rustc            134775 134774   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n15.895  build-script-bu  134781 134570   0 /target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build\n15.896  rustc            134778 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n15.897  rustc            134784 134781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n15.899  rustc            134783 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.102  rustc            134795 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.155  cross            134805 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n16.157  rustc            134807 134805   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.158  cross            134808 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.161  rustc            134812 134808   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.166  rustc            134807 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.171  rustc            134812 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.175  cross            134830 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n16.177  rustc            134836 134830   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.183  rustc            134846 134805   0 /home/xmoe/.cargo/bin/rustc -vV\n16.184  rustc            134836 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.188  rustc            134850 134808   0 /home/xmoe/.cargo/bin/rustc -vV\n16.194  rustc            134846 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.194  rustc            134850 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.197  rustc            134870 134830   0 /home/xmoe/.cargo/bin/rustc -vV\n16.203  rustc            134870 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.206  cargo            134881 134805   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.207  cargo            134882 134808   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.212  cargo            134881 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.212  cargo            134882 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.215  cargo            134900 134830   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.222  rustc            134904 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.223  cargo            134900 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n16.225  rustc            134913 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.225  rustc            134914 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.234  rustc            134920 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.236  rustc            134922 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.237  rustc            134921 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.246  rustc            134931 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.248  rustc            134932 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.248  rustc            134933 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.258  rustc            134943 134900   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.459  rustc            134970 134881   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.470  rustc            134972 134882   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.501  rustc            134975 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=147a2a5a42adf39c ...\n16.520  rustc            134979 134805   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.521  rustc            134980 134808   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.526  rustc            134979 134805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.526  rustc            134980 134808   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.528  rustc            134999 134830   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.534  rustc            134999 134830   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.538  docker           135023 134805   0 /usr/bin/docker --help\n16.539  docker           135022 134808   0 /usr/bin/docker --help\n16.542  cc               135024 134975   0 /tmp/native-trace-134348-1783993036926/shims/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcS6MiUq/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1cufun0.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.543  cc               135037 135024   0 /usr/bin/cc -m64 /target/debug/build/errno-dragonfly-230bb91007c5e395/rustcS6MiUq/symbols.o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.1cufun0.rcgu. /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.1cufun0.rcgu. -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf ...\n16.546  collect2         135040 135037   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.547  docker           135047 134830   0 /usr/bin/docker --help\n16.548  ld.lld           135048 135040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395 ...\n16.549  rust-lld         135048 135040   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuJoU85.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.553  docker           135055 134805   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.555  docker           135057 134808   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.560  docker           135072 134830   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.566  runc             135105 1599     0 /usr/bin/runc --version\n16.568  runc             135107 1599     0 /usr/bin/runc --version\n16.570  docker-init      135121 1599     0 /usr/bin/docker-init --version\n16.571  docker-init      135122 1599     0 /usr/bin/docker-init --version\n16.571  docker           135123 134808   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.573  docker           135124 134805   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.576  runc             135135 1599     0 /usr/bin/runc --version\n16.579  docker-init      135143 1599     0 /usr/bin/docker-init --version\n16.580  docker           135145 134830   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.586  runc             135157 1599     0 /usr/bin/runc --version\n16.587  runc             135158 1599     0 /usr/bin/runc --version\n16.590  16               135170 1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n16.591  docker-init      135174 1599     0 /usr/bin/docker-init --version\n16.591  docker-init      135175 1599     0 /usr/bin/docker-init --version\n16.593  16               135176 1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n16.596  runc             135182 1599     0 /usr/bin/runc --version\n16.600  docker-init      135188 1599     0 /usr/bin/docker-init --version\n16.617  rustup           135189 134808   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.621  rustup           135191 134805   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.625  rustup           135207 134808   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.627  rustup           135208 134830   0 \n16.628  rustup           135209 134805   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.633  rustup           135234 134830   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.640  build-script-bu  135244 134601   0 /target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build\n16.643  aarch64-linux-g  135245 135244   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/15304498930840454446detect_compiler_family.c\n16.645  cc1              135246 135245   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/15304498930840454446detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.652  aarch64-linux-g  135247 135244   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.655  rustup           135249 134808   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.656  aarch64-linux-g  135248 135244   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o -c src/errno.c\n16.658  rustup           135250 134805   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.658  cc1              135251 135248   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu src/errno.c -quiet -dumpbase errno.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o -g -gdwarf-4 -O0 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n16.662  rustup           135268 134830   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.674  as               135277 135248   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o /tmp/cculmR6Y.s\n16.684  uname            135278 134808   0 /usr/bin/uname -r\n16.686  uname            135279 134805   0 /usr/bin/uname -r\n16.686  aarch64-linux-g  135280 135244   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/liberrno.a /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/ea708c7824d36062-errno.o\n16.690  aarch64-linux-g  135281 135244   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/errno-dragonfly-e6c84ed6eefa2c0b/out/liberrno.a\n16.690  uname            135282 134830   0 /usr/bin/uname -r\n16.696  rustc            135284 134601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name errno_dragonfly --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=53b2dae70a4a483e ...\n16.705  docker           135286 134808   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.706  docker           135289 134805   0 \n16.711  docker           135300 134830   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.718  systemd-coredum  135170 1        0 /usr/lib/systemd/systemd-coredump\n16.722  drkonqi-coredum  135176 1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 902-135138-0\n16.776  systemd-sysctl   135329 135327   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe7f190c --prefix=/net/ipv4/neigh/vethe7f190c --prefix=/net/ipv6/conf/vethe7f190c --prefix=/net/ipv6/neigh/vethe7f190c\n16.778  systemd-sysctl   135332 135328   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth507313e --prefix=/net/ipv4/neigh/veth507313e --prefix=/net/ipv6/conf/veth507313e --prefix=/net/ipv6/neigh/veth507313e\n16.779  systemd-sysctl   135333 135331   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9babf0c --prefix=/net/ipv4/neigh/veth9babf0c --prefix=/net/ipv6/conf/veth9babf0c --prefix=/net/ipv6/neigh/veth9babf0c\n16.781  systemd-sysctl   135335 135334   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbafc3c1 --prefix=/net/ipv4/neigh/vethbafc3c1 --prefix=/net/ipv6/conf/vethbafc3c1 --prefix=/net/ipv6/neigh/vethbafc3c1\n16.810  cross            135367 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n16.811  rustc            135370 135367   0 /home/xmoe/.cargo/bin/rustc --print target-list\n16.816  rustc            135370 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n16.827  rustc            135384 135367   0 /home/xmoe/.cargo/bin/rustc -vV\n16.832  rustc            135384 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.834  9                135399 4003047   0 /proc/self/fd/9 --deserialize 30 --log-level info --log-target auto\n16.839  abrt-server      135400 1118     0 /usr/bin/abrt-server -s\n16.842  cargo            135402 135367   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.845  drkonqi-coredum  135399 4003047   0 /usr/libexec/drkonqi-coredump-launcher\n16.847  cargo            135402 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n16.858  rustc            135411 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.862  abrt-handle-eve  135412 135400   0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:37:20.224570-131780\n16.868  rustc            135414 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.875  sh               135419 135412   0 /bin/sh -c abrt-action-save-package-data\\n\n16.877  abrt-action-sav  135419 135412   0 /usr/bin/abrt-action-save-package-data\n16.880  rustc            135423 135402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.882  9                135424 4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n16.885  systemd-sysctl   135425 135359   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaf765b1 --prefix=/net/ipv4/neigh/vethaf765b1 --prefix=/net/ipv6/conf/vethaf765b1 --prefix=/net/ipv6/neigh/vethaf765b1\n16.885  systemd-sysctl   135426 135337   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethafd0901 --prefix=/net/ipv4/neigh/vethafd0901 --prefix=/net/ipv6/conf/vethafd0901 --prefix=/net/ipv6/neigh/vethafd0901\n16.888  plasma_waitforn  135424 4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n16.912  containerd-shim  135431 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 start\n16.915  containerd-shim  135438 135431   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 -address /var/run/docker/containerd/containerd.sock\n16.918  runc             135447 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n16.924  exe              135454 135447   0 /proc/self/exe init\n16.934  sh               135456 135412   0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n16.936  cat              135459 135457   0 /usr/bin/cat uid\n16.936  cut              135458 135456   0 /usr/bin/cut -d: -f1\n16.937  getent           135457 135456   0 /usr/bin/getent passwd 1000\n16.938  lscpu            135466 135456   0 /usr/bin/lscpu\n16.951  rustc            135468 135367   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.951  sh               135469 135412   0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n16.953  runlevel         135470 135469   0 /usr/bin/runlevel\n16.954  exe              135476 135447   0 /proc/1599/exe -exec-root=/var/run/docker c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 d7da31e8f8e1\n16.957  rustc            135468 135367   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.963  sh               135486 135412   0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n16.965  grep             135488 135486   0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n16.966  grep             135491 135486   0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n16.968  grep             135492 135486   0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n16.969  docker           135493 135367   0 /usr/bin/docker --help\n16.969  abrt-action-cor  135494 135486   0 /usr/libexec/abrt-action-coredump -x\n16.977  exe              135507 1599     0 /proc/self/exe /var/run/docker/netns/f309c401b495 all false\n16.982  docker           135513 135367   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.994  runc             135534 1599     0 /usr/bin/runc --version\n16.998  docker-init      135540 1599     0 /usr/bin/docker-init --version\n16.999  docker           135541 135367   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.011  runc             135552 1599     0 /usr/bin/runc --version\n17.015  docker-init      135558 1599     0 /usr/bin/docker-init --version\n17.026  abrt-action-gen  135559 135486   0 /usr/bin/abrt-action-generate-core-backtrace\n17.064  runc             135565 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup start c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n17.070  sh               135461 135438   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.071  cargo            135571 135461   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.071  abrt-action-ana  135572 135486   0 /usr/bin/abrt-action-analyze-vulnerability\n17.073  containerd-shim  135573 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f start\n17.074  eu-readelf       135575 135574   0 /usr/bin/eu-readelf -n coredump\n17.076  containerd-shim  135581 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3 start\n17.076  grep             135576 135574   0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n17.077  sed              135577 135574   0 /usr/bin/sed s/[^0-9]//g\n17.078  containerd-shim  135587 135573   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f -address /var/run/docker/containerd/containerd.sock\n17.080  containerd-shim  135595 135581   0 \n17.081  gdb              135598 135596   0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n17.083  runc             135606 135587   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f\n17.086  runc             135618 135595   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3\n17.088  cargo-native-tr  135571 135461   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.088  rustup           135619 135367   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.090  exe              135635 135606   0 /proc/self/exe init\n17.092  cargo            135636 135571   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.093  exe              135639 135618   0 /proc/self/exe init\n17.095  rustup           135643 135367   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.100  iconv            135652 135598   0 /usr/bin/iconv -l\n17.105  rustc            135653 135636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.117  rustc            135677 135636   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.123  rustup           135678 135367   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.130  exe              135690 135606   0 /proc/1599/exe -exec-root=/var/run/docker fc2d2bd215bcb04ee1bd43d84a2282beae4544e70865b7ff4f0f07b7a5c3410f d7da31e8f8e1\n17.132  exe              135691 135618   0 /proc/1599/exe -exec-root=/var/run/docker d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3 d7da31e8f8e1\n17.136  execsnoop        135702 135571   0 /usr/local/bin/execsnoop -t\n17.137  python3          135702 135571   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.150  uname            135707 135367   0 /usr/bin/uname -r\n17.155  exe              135709 1599     0 /proc/self/exe /var/run/docker/netns/fa5d3e6db347 all false\n17.156  exe              135710 1599     0 /proc/self/exe /var/run/docker/netns/e66f314cd096 all false\n17.170  docker           135738 135367   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.187  abrt-action-ana  135753 135486   0 /usr/bin/abrt-action-analyze-c\n17.197  eu-unstrip       135754 135753   0 /usr/bin/eu-unstrip --core=./coredump -n\n17.212  rustc            135758 134570   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2_diagnostics --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"colors\" --cfg feature=\"default\" --cfg feature=\"yansi\" ...\n17.213  abrt-action-lis  135759 135486   0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n17.220  systemd-sysctl   135760 135337   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth317a84f --prefix=/net/ipv4/neigh/veth317a84f --prefix=/net/ipv6/conf/veth317a84f --prefix=/net/ipv6/neigh/veth317a84f\n17.221  systemd-sysctl   135761 135359   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4d6bdd7 --prefix=/net/ipv4/neigh/veth4d6bdd7 --prefix=/net/ipv6/conf/veth4d6bdd7 --prefix=/net/ipv6/neigh/veth4d6bdd7\n17.226  runc             135766 135587   0 \n17.234  sh               135663 135587   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.236  cargo            135773 135663   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.238  runc             135774 135595   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b --log-format json --systemd-cgroup start d492cc1f7029465eb444731e67c416cb773a78f5fff0500a2b72726c52b298b3\n17.245  sh               135670 135595   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.247  cargo            135780 135670   0 \n17.251  cargo-native-tr  135773 135663   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.256  cargo            135781 135773   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.260  cargo-native-tr  135780 135670   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.265  cargo            135783 135780   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.270  rustc            135784 135781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.278  rustc            135785 135783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.279  cat              135788 135787   0 /usr/bin/cat executable\n17.280  cat              135789 135787   0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:37:20.224570-131780/uid\n17.282  journalctl       135791 135787   0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n17.284  rustc            135790 135781   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.294  rustc            135794 135783   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.295  containerd-shim  135797 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 start\n17.298  abrt-action-cor  135802 135486   0 /usr/libexec/abrt-action-coredump -r\n17.300  containerd-shim  135805 135797   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 -address /var/run/docker/containerd/containerd.sock\n17.305  runc             135818 135805   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009\n17.310  execsnoop        135825 135773   0 /usr/local/bin/execsnoop -t\n17.310  python3          135825 135773   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.314  exe              135829 135818   0 /proc/self/exe init\n17.361  exe              135841 135818   0 /proc/1599/exe -exec-root=/var/run/docker 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009 d7da31e8f8e1\n17.372  abrt-handle-eve  135849 135400   0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.386  sh               135857 135849   0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n17.390  dbus-send        135857 135849   0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.396  sh               135865 135849   0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n17.399  abrt-action-not  135868 135865   0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n17.401  exe              135869 1599     0 /proc/self/exe /var/run/docker/netns/bce91fa060ac all false\n17.472  execsnoop        135929 135780   0 /usr/local/bin/execsnoop -t\n17.474  runc             135931 135805   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a --log-format json --systemd-cgroup start 2c48cd9350d921d6f5e99ff66bee5325fa532c4a51ccfa58a9e1184c60a6b009\n17.474  python3          135929 135780   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.481  sh               135834 135805   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.483  cargo            135939 135834   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.492  sh               135941 135868   0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n17.493  reporter-system  135941 135868   0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.501  cargo-native-tr  135939 135834   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.507  cargo            135943 135939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.524  rustc            135947 135943   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.538  rustc            135949 135943   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.653  execsnoop        135956 135939   0 /usr/local/bin/execsnoop -t\n17.655  python3          135956 135939   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
    },
    {
      "argv": [
        "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 129677,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
      "pid": 129677,
      "ppid": 129424,
      "root_cargo_pid": 129424,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 129677,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 129679,
      "ppid": 129677,
      "root_cargo_pid": 129424,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_7dd9ae61cfa3d8f9_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/rand_pcg-fa4faf33fee0fa1d/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 129677,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 129686,
      "ppid": 129677,
      "root_cargo_pid": 129424,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rand_pcg",
      "cwd": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "event_id": "bsrun:d4f667fd5c8557bb:5c4fb2aca3f401de:8c840e32d1f630fc",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
      "out_dir": "/target/debug/build/rand_pcg-a9cc825a09faf9c5/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "rand_pcg",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2#rand_pcg@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-yqw2sbkn/src/rand_pcg-0.1.2",
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
      "build_script_root_pid": 129677,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 129679,
      "ppid": 129677,
      "root_cargo_pid": 129424,
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
        "autocfg_7dd9ae61cfa3d8f9_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/rand_pcg-fa4faf33fee0fa1d/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 129677,
      "build_script_target_dir": "rand_pcg-a9cc825a09faf9c5",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 129686,
      "ppid": 129677,
      "root_cargo_pid": 129424,
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
