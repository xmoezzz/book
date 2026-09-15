# `sha2-asm` `0.6.4`

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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
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
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
    "/target/debug/build/sha2-asm-e0eb8c965c490186",
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
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-412082-1783994380876439136.map",
  "pid": 412082,
  "ppid": 412038,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-412082-1783994380876439136.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a`

Owner: `sha2-asm` `0.6.4`

### Source files

* `/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/src/sha256_aarch64.S`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-Wall",
    "-Wextra",
    "-march=armv8-a+crypto",
    "-c",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
    "-c",
    "src/sha256_aarch64.S"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 412201,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/sha256_aarch64.S",
    "-march=armv8-a+crypto",
    "-mlittle-endian",
    "-mabi=lp64",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-fno-omit-frame-pointer",
    "-g",
    "-gdwarf-4",
    "-fworking-directory",
    "-O0",
    "..."
  ],
  "src": "src/sha256_aarch64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 412202,
  "ppid": 412201,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "root_cargo_pid": 411794,
  "build_script_root_pid": 412173,
  "build_script_related": true,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 412231,
  "ppid": 412173,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "root_cargo_pid": 411794,
  "build_script_root_pid": 412173,
  "build_script_related": true,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

### Native link records

_None._

### Resolved link records

_None._

### Resolved native inputs

_None._

## Complete analysis record stream

These are the recovered/enriched/generated records actually supplied to native-flow reconstruction.

### Analysis records

#### Record 1

```json
{
  "event": "native_trace_root_context",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "workspace_root": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
      "name": "sha2-asm",
      "version": "0.6.4",
      "manifest_path": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    }
  ],
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 412082,
  "ppid": 412038,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:2418f9e5eba3b9c9:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
  "pid": 412082,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:40517608ef7e184b:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "db2b886b2791c7cc5c9d40479f0bfea3ffc1a239ff98c12a44daaf50eb62ff47",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:15cbc5f37a16a7bb:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "0ecf48a956857edab2a1810c9c08299f46fbf503ff4f28bd7b82507e512db7b7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:c942c8bcd032b43d:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "64b121ecee3cede296922ef4c7305658c6f0264f2c0c03e759a36e4d8dca0514",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:55c52a6a4c5711ce:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "74f331d23044b8ab7f4b8a8561bc9191c164f93eea89cc80ea4607854f3117f1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:8be06085f75da831:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "1a30e80c4872fa801978b47f81629828d94457cc5a9cbeac77bcd3efef35358c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:e648cc2fce0b3757:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "49087eecfc8c5287fc0d001e8093e855bcb3ee1addf9413abfd192fb2bd73485",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:96b32b35b6b444bb:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "885c16d0bc53ea70ec7d501624e6132b714b8c18ce00d2517e05588aea57ed73",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:46f5489236875a22:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "213e08c0c789f752a870abf160e900dfd705400ce1289971cdaa680913f403c7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:076a54099b8b5247:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "f5299452a26a1c4aa0baaabefb0a538039ca39c68d857b641102be1935873409",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:aa02d93c4548b96c:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "efa198e0f14ed670909cf5dd58a175fe6ed0c97c2e7528509e70f232f2fcb41e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "used:cc:b49a1434cbfcb411:3300724b106332c2:f9f0777cd0732ee1",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
  "pid": 412082,
  "sha256": "db2f701451adb4abb41ac5eeb4cf0eabc7b04801862c0cfcb3f871beda2530e9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
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
  "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 16

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "cargo_pkg_name": "sha2-asm",
  "cargo_pkg_version": "0.6.4",
  "context_path": "/tmp/native-trace-411260-1783994376949/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-411260-1783994376949/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 412082,
  "ppid": 412038,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 17

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
    "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
    "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
    "/target/debug/build/sha2-asm-e0eb8c965c490186",
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
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
      "kind": "object",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-412082-1783994380876439136.map",
  "pid": 412082,
  "ppid": 412038,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-412082-1783994380876439136.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

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

#### Record 19

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 782,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 783,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "ystemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3002929 --prefix=/net/ipv4/neigh/veth3002929 --prefix=/net/ipv6/conf/veth3002929 --prefix=/net/ipv6/neigh/veth3002929\n14.835  rustc            415618 415351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.897  rustc            415623 415480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.956  rustc            415628 415524   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.081  rustc            415634 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling_macro --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling_macro-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n15.161  cc               415642 415634   0 /tmp/native-trace-414637-1783994389094/shims/cc -Wl,--version-script=/target/debug/deps/rustcWwIpDQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWwIpDQ/symbols.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.0.rcgu.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.1.rcgu.o /target/debug/deps/rustcWwIpDQ/rmeta.o /target/debug/deps/darling_macro-fb00e23033ac236c.5b8aj36r7b5y3zb2uc9rg3i23.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n15.162  cc               415643 415642   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcWwIpDQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWwIpDQ/symbols.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.0.rcgu.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.1.rcgu.o /target/debug/deps/rustcWwIpDQ/rmeta.o /target/debug/deps/darling_macro-fb00e23033ac236c.5b8aj36r7b5y3zb2uc9rg3i23.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n15.164  collect2         415644 415643   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWwIpDQ/raw-dylibs ...\n15.166  ld.lld           415645 415644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWwIpDQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.167  rust-lld         415645 415644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.294  rustc            415663 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"suggestions\" --check-cfg cfg(docsrs,test) ...\n15.313  rustc            415671 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder_core-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lib_has_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"clippy\", \"lib_has_std\")) ...\n15.532  rustc            415675 415499   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.537  rustc            415675 415499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.542  rustc            415684 415326   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.548  rustc            415684 415326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.549  docker           415696 415499   0 /usr/bin/docker --help\n15.556  rustc            415702 415455   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.561  docker           415720 415326   0 /usr/bin/docker --help\n15.562  rustc            415702 415455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.563  docker           415721 415499   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.574  docker           415746 415455   0 /usr/bin/docker --help\n15.575  runc             415747 1599     0 /usr/bin/runc --version\n15.576  docker           415752 415326   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.578  docker-init      415760 1599     0 /usr/bin/docker-init --version\n15.579  docker           415765 415499   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.588  runc             415787 1599     0 /usr/bin/runc --version\n15.589  docker           415788 415455   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.591  docker-init      415794 1599     0 /usr/bin/docker-init --version\n15.591  runc             415798 1599     0 /usr/bin/runc --version\n15.594  docker           415805 415326   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.595  docker-init      415807 1599     0 /usr/bin/docker-init --version\n15.602  runc             415827 1599     0 /usr/bin/runc --version\n15.606  docker-init      415833 1599     0 /usr/bin/docker-init --version\n15.607  docker           415834 415455   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.608  runc             415835 1599     0 /usr/bin/runc --version\n15.612  docker-init      415846 1599     0 /usr/bin/docker-init --version\n15.620  runc             415851 1599     0 /usr/bin/runc --version\n15.622  rustup           415857 415499   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.623  docker-init      415858 1599     0 /usr/bin/docker-init --version\n15.628  rustup           415869 415499   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.637  rustup           415878 415326   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.643  rustup           415887 415326   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.646  rustup           415896 415455   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.652  rustup           415905 415455   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.654  rustup           415908 415499   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.668  rustup           415925 415326   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.677  rustup           415935 415455   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.682  uname            415944 415499   0 /usr/bin/uname -r\n15.698  uname            415946 415326   0 /usr/bin/uname -r\n15.700  docker           415948 415499   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.704  uname            415954 415455   0 /usr/bin/uname -r\n15.719  docker           415963 415326   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.726  docker           415969 415455   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.759  systemd-sysctl   415990 415606   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth070cd19 --prefix=/net/ipv4/neigh/veth070cd19 --prefix=/net/ipv6/conf/veth070cd19 --prefix=/net/ipv6/neigh/veth070cd19\n15.759  systemd-sysctl   415989 415596   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth871c786 --prefix=/net/ipv4/neigh/veth871c786 --prefix=/net/ipv6/conf/veth871c786 --prefix=/net/ipv6/neigh/veth871c786\n15.796  containerd-shim  416028 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 start\n15.799  systemd-sysctl   416032 415998   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4403068 --prefix=/net/ipv4/neigh/veth4403068 --prefix=/net/ipv6/conf/veth4403068 --prefix=/net/ipv6/neigh/veth4403068\n15.799  systemd-sysctl   416033 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha312152 --prefix=/net/ipv4/neigh/vetha312152 --prefix=/net/ipv6/conf/vetha312152 --prefix=/net/ipv6/neigh/vetha312152\n15.800  containerd-shim  416036 416028   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 -address /var/run/docker/containerd/containerd.sock\n15.805  runc             416048 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n15.808  systemd-sysctl   416050 416000   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8a42784 --prefix=/net/ipv4/neigh/veth8a42784 --prefix=/net/ipv6/conf/veth8a42784 --prefix=/net/ipv6/neigh/veth8a42784\n15.808  systemd-sysctl   416052 416005   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7edf8f3 --prefix=/net/ipv4/neigh/veth7edf8f3 --prefix=/net/ipv6/conf/veth7edf8f3 --prefix=/net/ipv6/neigh/veth7edf8f3\n15.820  exe              416064 416048   0 /proc/self/exe init\n15.828  containerd-shim  416065 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 start\n15.832  containerd-shim  416072 416065   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 -address /var/run/docker/containerd/containerd.sock\n15.836  runc             416082 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n15.842  exe              416097 416082   0 /proc/self/exe init\n15.855  exe              416105 416048   0 /proc/1599/exe -exec-root=/var/run/docker 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 d7da31e8f8e1\n15.863  rustc            416112 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder_macro-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lib_has_std\" --check-cfg cfg(docsrs,test) ...\n15.865  exe              416113 416082   0 /proc/1599/exe -exec-root=/var/run/docker 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 d7da31e8f8e1\n15.872  containerd-shim  416121 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 start\n15.875  containerd-shim  416130 416121   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 -address /var/run/docker/containerd/containerd.sock\n15.881  runc             416142 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n15.883  exe              416148 1599     0 /proc/self/exe /var/run/docker/netns/1920a79c4c7c all false\n15.888  exe              416156 416142   0 /proc/self/exe init\n15.891  exe              416159 1599     0 /proc/self/exe /var/run/docker/netns/33d02db33c19 all false\n15.923  exe              416193 416142   0 /proc/1599/exe -exec-root=/var/run/docker 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 d7da31e8f8e1\n15.936  runc             416201 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup start 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n15.941  sh               416089 416036   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.942  cargo            416208 416089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.945  exe              416209 1599     0 /proc/self/exe /var/run/docker/netns/cbf882515669 all false\n15.951  runc             416217 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup start 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n15.952  cc               416216 416112   0 /tmp/native-trace-414637-1783994389094/shims/cc -Wl,--version-script=/target/debug/deps/rustcv50UxG/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv50UxG/symbols.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.derive_builder_macro.1b3a0c97b623ae1e-cgu.0.rcgu.o /target/debug/deps/rustcv50UxG/rmeta.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.5xiavdlm02le18eofow3z1yph.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libderive_builder_core-6ca14b448848b816.rlib /target/debug/deps/libdarling-ff1a4109f3008e61.rlib /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib ...\n15.953  cc               416221 416216   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcv50UxG/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv50UxG/symbols.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.derive_builder_macro.1b3a0c97b623ae1e-cgu.0.rcgu.o /target/debug/deps/rustcv50UxG/rmeta.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.5xiavdlm02le18eofow3z1yph.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libderive_builder_core-6ca14b448848b816.rlib /target/debug/deps/libdarling-ff1a4109f3008e61.rlib /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib ...\n15.955  cargo-native-tr  416208 416089   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.956  collect2         416226 416221   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv50UxG/raw-dylibs ...\n15.957  sh               416099 416072   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.958  ld.lld           416227 416226   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv50UxG/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.959  cargo            416233 416208   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.960  rust-lld         416227 416226   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.961  cargo            416234 416099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n15.971  rustc            416238 416233   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.972  cargo-native-tr  416234 416099   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n15.976  cargo            416239 416234   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.983  rustc            416253 416233   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.989  rustc            416258 416239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.994  runc             416262 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup start 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n16.000  sh               416177 416130   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.001  cargo            416270 416177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.002  rustc            416269 416239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.013  cargo-native-tr  416270 416177   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.017  cargo            416274 416270   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.029  rustc            416275 416274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.041  rustc            416277 416274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.044  execsnoop        416278 416208   0 /usr/local/bin/execsnoop -t\n16.044  python3          416278 416208   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.068  execsnoop        416284 416234   0 /usr/local/bin/execsnoop -t\n16.069  python3          416284 416234   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.097  execsnoop        416287 416270   0 /usr/local/bin/execsnoop -t\n16.098  python3          416287 416270   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.116  rustc            416291 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(compiletests) --cfg feature=\"default\" --cfg ...\n16.149  rustc            416298 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name vergen_lib --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"build\", \"cargo\", \"default\", \"emit_and_set\", \"git\", \"rustc\", \"si\", \"unstable\")) ...\n17.008  16               416380 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.023  frpc             416380 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.238  runc             416387 407725   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e --log-format json --systemd-cgroup kill --all 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57 9\n17.256  runc             416393 407725   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e --log-format json --systemd-cgroup delete 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57\n17.275  runc             416400 410520   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b --log-format json --systemd-cgroup kill --all 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d 9\n17.278  runc             416407 410612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 --log-format json --systemd-cgroup kill --all d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa 9\n17.280  git              416399 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.282  runc             416413 410520   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b --log-format json --systemd-cgroup delete 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d\n17.288  runc             416419 410612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 --log-format json --systemd-cgroup delete d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa\n17.530  containerd-shim  416425 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e delete\n17.532  runc             416432 416425   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae5 --log-format json delete --force 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57\n17.571  sh               416439 416001   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethac8d5d9\n17.572  ethtool          416440 416439   0 /usr/sbin/ethtool -i vethac8d5d9\n17.573  sed              416441 416439   0 /usr/bin/sed -n s/^driver: //p\n17.575  containerd-shim  416444 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b delete\n17.577  runc             416451 416444   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884 --log-format json delete --force 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d\n17.578  systemd-sysctl   416452 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac8d5d9 --prefix=/net/ipv4/neigh/vethac8d5d9 --prefix=/net/ipv6/conf/vethac8d5d9 --prefix=/net/ipv6/neigh/vethac8d5d9\n17.610  containerd-shim  416457 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 delete\n17.612  runc             416464 416457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2f --log-format json delete --force d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa\n17.649  systemd-sysctl   416469 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a2351a --prefix=/net/ipv4/neigh/veth3a2351a --prefix=/net/ipv6/conf/veth3a2351a --prefix=/net/ipv6/neigh/veth3a2351a\n17.650  systemd-sysctl   416470 415998   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethed35d5c --prefix=/net/ipv4/neigh/vethed35d5c --prefix=/net/ipv6/conf/vethed35d5c --prefix=/net/ipv6/neigh/vethed35d5c\n17.786  runc             416471 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1390342900 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.791  exe              416479 416471   0 /proc/self/exe init\n17.812  etcdctl          416481 416471   0 /usr/local/bin/etcdctl endpoint health\n18.042  cargo            416494 416234   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.053  cargo            416495 416270   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.057  rustc            416496 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.066  rustc            416498 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.099  rustc            416513 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.100  rustc            416514 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.101  rustc            416518 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=4400a25aaf223f04 ...\n18.102  rustc            416516 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=f2162428cb92f352 ...\n18.104  rustc            416519 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=e61b9f04f0d50a75 ...\n18.104  rustc            416520 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.104  rustc            416521 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.107  rustc            416517 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=1a810a4b3f0efeb6 ...\n18.242  cc               416576 416513   0 /tmp/native-trace-416270-1783994395653/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcEIgHYR/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.243  cc               416578 416576   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcEIgHYR/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.245  cc               416577 416514   0 /tmp/native-trace-416234-1783994395612/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcFfMWUc/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.247  cc               416579 416577   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcFfMWUc/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.248  collect2         416580 416578   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  collect2         416583 416579   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  ld.lld           416582 416580   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n18.253  ld.lld           416584 416583   0 \n18.253  rust-lld         416582 416580   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.255  rust-lld         416584 416583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.257  sh               416586 2147557   0 /bin/sh -c which ps\n18.259  which            416586 2147557   0 /usr/bin/which ps\n18.262  sh               416587 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.264  ps               416587 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.294  rustc            416621 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"debug\", \"pool\", \"proptest\", \"quickcheck\", \"rayon\", \"refpool\", \"serde\")) -C metadata=1984f889580b2e34 ...\n18.298  rustc            416623 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"debug\", \"pool\", \"proptest\", \"quickcheck\", \"rayon\", \"refpool\", \"serde\")) -C metadata=1984f889580b2e34 ...\n18.300  sh               416624 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.302  cpuUsage.sh      416624 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.303  sed              416625 416624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.306  cat              416629 416624   0 /usr/bin/cat /proc/2240539/stat\n18.308  cat              416630 416624   0 /usr/bin/cat /proc/4193716/stat\n18.310  sleep            416631 416624   0 /usr/bin/sleep 1\n18.324  build-script-bu  416637 416494   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n18.325  build-script-bu  416638 416495   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n18.327  rustc            416639 416638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.327  rustc            416640 416637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.346  rustc            416658 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.347  rustc            416656 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.356  cc               416675 416621   0 /tmp/native-trace-416270-1783994395653/shims/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustc0NYk8i/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.1hodkv8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.358  cc               416682 416675   0 /usr/bin/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustc0NYk8i/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.1hodkv8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.359  cargo            416683 416208   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.361  collect2         416685 416682   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.362  cc               416684 416623   0 /tmp/native-trace-416234-1783994395612/shims/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustcsDKD2Z/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.0bp0ikg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.364  cc               416686 416684   0 \n18.364  ld.lld           416687 416685   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257 ...\n18.366  rust-lld         416687 416685   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.367  collect2         416688 416686   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.370  ld.lld           416689 416688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257 ...\n18.372  rust-lld         416689 416688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.379  rustc            416690 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.405  cross            416726 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n18.406  rustc            416729 416726   0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.413  rustc            416729 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.420  rustc            416745 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.420  rustc            416742 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.423  rustc            416744 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=ef45cdee1882644b ...\n18.428  rustc            416746 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=d8ce8a727baff604 ...\n18.429  rustc            416750 416726   0 /home/xmoe/.cargo/bin/rustc -vV\n18.437  rustc            416750 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.438  build-script-bu  416769 416495   0 /target/debug/build/im-rc-8dc1db58054b3257/build-script-build\n18.442  rustc            416770 416769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n18.451  cargo            416778 416726   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.456  build-script-bu  416789 416494   0 /target/debug/build/im-rc-8dc1db58054b3257/build-script-build\n18.458  cargo            416778 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.460  rustc            416790 416789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n"
}
```

#### Record 20

```json
{
  "argv": [
    "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build",
  "pid": 412173,
  "ppid": 411794,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out"
}
```

#### Record 21

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/3020265423487988854detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 412176,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/3020265423487988854detect_compiler_family.c",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 412178,
  "ppid": 412176,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 412186,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-Wall",
    "-Wextra",
    "-march=armv8-a+crypto",
    "-c",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
    "-c",
    "src/sha256_aarch64.S"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-gcc",
  "pid": 412201,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/sha256_aarch64.S",
    "-march=armv8-a+crypto",
    "-mlittle-endian",
    "-mabi=lp64",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-fno-omit-frame-pointer",
    "-g",
    "-gdwarf-4",
    "-fworking-directory",
    "-O0",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "pid": 412202,
  "ppid": 412201,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "--gdwarf2",
    "-EL",
    "-march=armv8-a+crypto",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
    "/tmp/ccJ6QezS.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 412209,
  "ppid": 412201,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 27

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 412231,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 412173,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 412235,
  "ppid": 412173,
  "root_cargo_pid": 411794,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "crate": "sha2-asm",
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "event_id": "bsrun:dacd6b7cde7481e1:1030ac0be42b35c9:ba0670e4edc2a9ee",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
  "success": true,
  "target": null,
  "version": "0.6.4",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  }
}
```

#### Record 30

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
    "-E",
    "-lang-asm",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "src/sha256_aarch64.S",
    "-march=armv8-a+crypto",
    "-mlittle-endian",
    "-mabi=lp64",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-fno-omit-frame-pointer",
    "-g",
    "-gdwarf-4",
    "-fworking-directory",
    "-O0",
    "..."
  ],
  "src": "src/sha256_aarch64.S",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 412202,
  "ppid": 412201,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "root_cargo_pid": 411794,
  "build_script_root_pid": 412173,
  "build_script_related": true,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 31

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 412231,
  "ppid": 412173,
  "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "root_cargo_pid": 411794,
  "build_script_root_pid": 412173,
  "build_script_related": true,
  "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
  "_owner": {
    "crate": "sha2-asm",
    "version": "0.6.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
    "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
  "_build_script_out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:59:58.436354+00:00",
  "crate": "sha2-asm",
  "version": "0.6.4",
  "architecture": "aarch64",
  "duration_seconds": 26.395229015965015,
  "trace_record_count": 29,
  "trace_owner_summary": {
    "owner_package_count": 4,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "2.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml"
      },
      {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "manifest_path": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 18,
    "unattributed_event_count": 11,
    "owners": [
      {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "event_count": 18,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 12,
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
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "workspace_root": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
          "name": "sha2-asm",
          "version": "0.6.4",
          "manifest_path": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        }
      ],
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 412082,
      "ppid": 412038,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:2418f9e5eba3b9c9:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
      "pid": 412082,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:40517608ef7e184b:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "db2b886b2791c7cc5c9d40479f0bfea3ffc1a239ff98c12a44daaf50eb62ff47",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:15cbc5f37a16a7bb:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "0ecf48a956857edab2a1810c9c08299f46fbf503ff4f28bd7b82507e512db7b7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:c942c8bcd032b43d:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "64b121ecee3cede296922ef4c7305658c6f0264f2c0c03e759a36e4d8dca0514",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:55c52a6a4c5711ce:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "74f331d23044b8ab7f4b8a8561bc9191c164f93eea89cc80ea4607854f3117f1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:8be06085f75da831:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "1a30e80c4872fa801978b47f81629828d94457cc5a9cbeac77bcd3efef35358c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:e648cc2fce0b3757:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "49087eecfc8c5287fc0d001e8093e855bcb3ee1addf9413abfd192fb2bd73485",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:96b32b35b6b444bb:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "885c16d0bc53ea70ec7d501624e6132b714b8c18ce00d2517e05588aea57ed73",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:46f5489236875a22:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "213e08c0c789f752a870abf160e900dfd705400ce1289971cdaa680913f403c7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:076a54099b8b5247:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "f5299452a26a1c4aa0baaabefb0a538039ca39c68d857b641102be1935873409",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:aa02d93c4548b96c:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "efa198e0f14ed670909cf5dd58a175fe6ed0c97c2e7528509e70f232f2fcb41e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "used:cc:b49a1434cbfcb411:3300724b106332c2:f9f0777cd0732ee1",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
      "pid": 412082,
      "sha256": "db2f701451adb4abb41ac5eeb4cf0eabc7b04801862c0cfcb3f871beda2530e9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
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
      "output": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "cargo_pkg_name": "sha2-asm",
      "cargo_pkg_version": "0.6.4",
      "context_path": "/tmp/native-trace-411260-1783994376949/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-411260-1783994376949/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 412082,
      "ppid": 412038,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib",
        "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib",
        "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
        "/target/debug/build/sha2-asm-e0eb8c965c490186",
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
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/rustcpwnOjQ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.0ykjxmp9qxzfbvw87d2f1vkrd.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1avxzqjhc915g4o9o0kbcw7r2.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.1qolcavibxiklkaztk473mquq.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.27lfslugjp5oqnqvkanp67j41.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.3bso8eqo56hby27an5yk73vr8.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.7yca4j9dr5mbgsj2ullyjest5.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.9weibn47sve0mme5u44dfnvvu.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.amjvt0sslokpcj8zerl8q08f0.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.bp09zkj3m1q7k3jotgysg6e7h.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.elu61thyioaow5by6o68iyhhq.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/sha2-asm-e0eb8c965c490186",
          "kind": "object",
          "path": "/target/debug/build/sha2-asm-e0eb8c965c490186/build_script_build-e0eb8c965c490186.82wqsfi3y9hlawkkbq88nbzzo.0cl2e1l.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7fea9c8da0fe21a4.rlib(cc-7fea9c8da0fe21a4.cc.7f9270fe35c7c701-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib(find_msvc_tools-60e3732174de9068.find_msvc_tools.ede48c3253d6796d-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libshlex-f2fa52250b1d670f.rlib(shlex-f2fa52250b1d670f.shlex.352c8e657ac65ae8-cgu.0.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-412082-1783994380876439136.map",
      "pid": 412082,
      "ppid": 412038,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-412082-1783994380876439136.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
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
      "parsed_event_count": 782,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 783,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "ystemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3002929 --prefix=/net/ipv4/neigh/veth3002929 --prefix=/net/ipv6/conf/veth3002929 --prefix=/net/ipv6/neigh/veth3002929\n14.835  rustc            415618 415351   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.897  rustc            415623 415480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.956  rustc            415628 415524   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.081  rustc            415634 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling_macro --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling_macro-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n15.161  cc               415642 415634   0 /tmp/native-trace-414637-1783994389094/shims/cc -Wl,--version-script=/target/debug/deps/rustcWwIpDQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWwIpDQ/symbols.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.0.rcgu.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.1.rcgu.o /target/debug/deps/rustcWwIpDQ/rmeta.o /target/debug/deps/darling_macro-fb00e23033ac236c.5b8aj36r7b5y3zb2uc9rg3i23.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n15.162  cc               415643 415642   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcWwIpDQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcWwIpDQ/symbols.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.0.rcgu.o /target/debug/deps/darling_macro-fb00e23033ac236c.darling_macro.7e8595611c36a7fb-cgu.1.rcgu.o /target/debug/deps/rustcWwIpDQ/rmeta.o /target/debug/deps/darling_macro-fb00e23033ac236c.5b8aj36r7b5y3zb2uc9rg3i23.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 ...\n15.164  collect2         415644 415643   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWwIpDQ/raw-dylibs ...\n15.166  ld.lld           415645 415644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcWwIpDQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.167  rust-lld         415645 415644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccO93kHa.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libdarling_macro-fb00e23033ac236c.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.294  rustc            415663 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name darling --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/darling-0.20.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"suggestions\" --check-cfg cfg(docsrs,test) ...\n15.313  rustc            415671 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder_core-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lib_has_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"clippy\", \"lib_has_std\")) ...\n15.532  rustc            415675 415499   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.537  rustc            415675 415499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.542  rustc            415684 415326   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.548  rustc            415684 415326   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.549  docker           415696 415499   0 /usr/bin/docker --help\n15.556  rustc            415702 415455   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.561  docker           415720 415326   0 /usr/bin/docker --help\n15.562  rustc            415702 415455   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.563  docker           415721 415499   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.574  docker           415746 415455   0 /usr/bin/docker --help\n15.575  runc             415747 1599     0 /usr/bin/runc --version\n15.576  docker           415752 415326   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.578  docker-init      415760 1599     0 /usr/bin/docker-init --version\n15.579  docker           415765 415499   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.588  runc             415787 1599     0 /usr/bin/runc --version\n15.589  docker           415788 415455   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.591  docker-init      415794 1599     0 /usr/bin/docker-init --version\n15.591  runc             415798 1599     0 /usr/bin/runc --version\n15.594  docker           415805 415326   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.595  docker-init      415807 1599     0 /usr/bin/docker-init --version\n15.602  runc             415827 1599     0 /usr/bin/runc --version\n15.606  docker-init      415833 1599     0 /usr/bin/docker-init --version\n15.607  docker           415834 415455   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.608  runc             415835 1599     0 /usr/bin/runc --version\n15.612  docker-init      415846 1599     0 /usr/bin/docker-init --version\n15.620  runc             415851 1599     0 /usr/bin/runc --version\n15.622  rustup           415857 415499   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.623  docker-init      415858 1599     0 /usr/bin/docker-init --version\n15.628  rustup           415869 415499   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.637  rustup           415878 415326   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.643  rustup           415887 415326   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.646  rustup           415896 415455   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.652  rustup           415905 415455   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.654  rustup           415908 415499   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.668  rustup           415925 415326   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.677  rustup           415935 415455   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.682  uname            415944 415499   0 /usr/bin/uname -r\n15.698  uname            415946 415326   0 /usr/bin/uname -r\n15.700  docker           415948 415499   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.704  uname            415954 415455   0 /usr/bin/uname -r\n15.719  docker           415963 415326   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.726  docker           415969 415455   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.759  systemd-sysctl   415990 415606   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth070cd19 --prefix=/net/ipv4/neigh/veth070cd19 --prefix=/net/ipv6/conf/veth070cd19 --prefix=/net/ipv6/neigh/veth070cd19\n15.759  systemd-sysctl   415989 415596   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth871c786 --prefix=/net/ipv4/neigh/veth871c786 --prefix=/net/ipv6/conf/veth871c786 --prefix=/net/ipv6/neigh/veth871c786\n15.796  containerd-shim  416028 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 start\n15.799  systemd-sysctl   416032 415998   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4403068 --prefix=/net/ipv4/neigh/veth4403068 --prefix=/net/ipv6/conf/veth4403068 --prefix=/net/ipv6/neigh/veth4403068\n15.799  systemd-sysctl   416033 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha312152 --prefix=/net/ipv4/neigh/vetha312152 --prefix=/net/ipv6/conf/vetha312152 --prefix=/net/ipv6/neigh/vetha312152\n15.800  containerd-shim  416036 416028   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 -address /var/run/docker/containerd/containerd.sock\n15.805  runc             416048 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n15.808  systemd-sysctl   416050 416000   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8a42784 --prefix=/net/ipv4/neigh/veth8a42784 --prefix=/net/ipv6/conf/veth8a42784 --prefix=/net/ipv6/neigh/veth8a42784\n15.808  systemd-sysctl   416052 416005   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7edf8f3 --prefix=/net/ipv4/neigh/veth7edf8f3 --prefix=/net/ipv6/conf/veth7edf8f3 --prefix=/net/ipv6/neigh/veth7edf8f3\n15.820  exe              416064 416048   0 /proc/self/exe init\n15.828  containerd-shim  416065 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 start\n15.832  containerd-shim  416072 416065   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 -address /var/run/docker/containerd/containerd.sock\n15.836  runc             416082 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n15.842  exe              416097 416082   0 /proc/self/exe init\n15.855  exe              416105 416048   0 /proc/1599/exe -exec-root=/var/run/docker 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 d7da31e8f8e1\n15.863  rustc            416112 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder_macro --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder_macro-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lib_has_std\" --check-cfg cfg(docsrs,test) ...\n15.865  exe              416113 416082   0 /proc/1599/exe -exec-root=/var/run/docker 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 d7da31e8f8e1\n15.872  containerd-shim  416121 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 start\n15.875  containerd-shim  416130 416121   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 -address /var/run/docker/containerd/containerd.sock\n15.881  runc             416142 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n15.883  exe              416148 1599     0 /proc/self/exe /var/run/docker/netns/1920a79c4c7c all false\n15.888  exe              416156 416142   0 /proc/self/exe init\n15.891  exe              416159 1599     0 /proc/self/exe /var/run/docker/netns/33d02db33c19 all false\n15.923  exe              416193 416142   0 /proc/1599/exe -exec-root=/var/run/docker 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 d7da31e8f8e1\n15.936  runc             416201 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup start 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n15.941  sh               416089 416036   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.942  cargo            416208 416089   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.945  exe              416209 1599     0 /proc/self/exe /var/run/docker/netns/cbf882515669 all false\n15.951  runc             416217 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup start 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n15.952  cc               416216 416112   0 /tmp/native-trace-414637-1783994389094/shims/cc -Wl,--version-script=/target/debug/deps/rustcv50UxG/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv50UxG/symbols.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.derive_builder_macro.1b3a0c97b623ae1e-cgu.0.rcgu.o /target/debug/deps/rustcv50UxG/rmeta.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.5xiavdlm02le18eofow3z1yph.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libderive_builder_core-6ca14b448848b816.rlib /target/debug/deps/libdarling-ff1a4109f3008e61.rlib /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib ...\n15.953  cc               416221 416216   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcv50UxG/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv50UxG/symbols.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.derive_builder_macro.1b3a0c97b623ae1e-cgu.0.rcgu.o /target/debug/deps/rustcv50UxG/rmeta.o /target/debug/deps/derive_builder_macro-7b980fef7c139a4d.5xiavdlm02le18eofow3z1yph.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libderive_builder_core-6ca14b448848b816.rlib /target/debug/deps/libdarling-ff1a4109f3008e61.rlib /target/debug/deps/libdarling_core-85a6048f894b91e8.rlib /target/debug/deps/libstrsim-a84462a1b39a8130.rlib /target/debug/deps/libfnv-ab3b3d0161207bc5.rlib /target/debug/deps/libident_case-16eecdfab8f3bf02.rlib /target/debug/deps/libsyn-a8590e564cc06297.rlib /target/debug/deps/libquote-683d5cd005d4e7e6.rlib /target/debug/deps/libproc_macro2-58ad7b3fdbc027d3.rlib /target/debug/deps/libunicode_ident-47e23302670b8a29.rlib ...\n15.955  cargo-native-tr  416208 416089   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.956  collect2         416226 416221   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv50UxG/raw-dylibs ...\n15.957  sh               416099 416072   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.958  ld.lld           416227 416226   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv50UxG/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.959  cargo            416233 416208   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.960  rust-lld         416227 416226   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccBW54mQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libderive_builder_macro-7b980fef7c139a4d.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.961  cargo            416234 416099   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n15.971  rustc            416238 416233   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.972  cargo-native-tr  416234 416099   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n15.976  cargo            416239 416234   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.983  rustc            416253 416233   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.989  rustc            416258 416239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.994  runc             416262 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup start 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n16.000  sh               416177 416130   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.001  cargo            416270 416177   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.002  rustc            416269 416239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.013  cargo-native-tr  416270 416177   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.017  cargo            416274 416270   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.029  rustc            416275 416274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.041  rustc            416277 416274   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.044  execsnoop        416278 416208   0 /usr/local/bin/execsnoop -t\n16.044  python3          416278 416208   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.068  execsnoop        416284 416234   0 /usr/local/bin/execsnoop -t\n16.069  python3          416284 416234   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.097  execsnoop        416287 416270   0 /usr/local/bin/execsnoop -t\n16.098  python3          416287 416270   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.116  rustc            416291 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name derive_builder --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/derive_builder-0.20.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(compiletests) --cfg feature=\"default\" --cfg ...\n16.149  rustc            416298 414823   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name vergen_lib --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"build\", \"cargo\", \"default\", \"emit_and_set\", \"git\", \"rustc\", \"si\", \"unstable\")) ...\n17.008  16               416380 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n17.023  frpc             416380 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.238  runc             416387 407725   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e --log-format json --systemd-cgroup kill --all 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57 9\n17.256  runc             416393 407725   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e --log-format json --systemd-cgroup delete 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57\n17.275  runc             416400 410520   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b --log-format json --systemd-cgroup kill --all 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d 9\n17.278  runc             416407 410612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 --log-format json --systemd-cgroup kill --all d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa 9\n17.280  git              416399 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.282  runc             416413 410520   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b --log-format json --systemd-cgroup delete 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d\n17.288  runc             416419 410612   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 --log-format json --systemd-cgroup delete d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa\n17.530  containerd-shim  416425 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2e delete\n17.532  runc             416432 416425   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae5 --log-format json delete --force 987c85edb5e96b041a0327f10f8511568615e69f4415d9fb2311455ae2eaae57\n17.571  sh               416439 416001   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethac8d5d9\n17.572  ethtool          416440 416439   0 /usr/sbin/ethtool -i vethac8d5d9\n17.573  sed              416441 416439   0 /usr/bin/sed -n s/^driver: //p\n17.575  containerd-shim  416444 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b delete\n17.577  runc             416451 416444   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884 --log-format json delete --force 4b5630fdde1ddaa4b401457e43ea40d671bb205a7544c60a017d69e530b6884d\n17.578  systemd-sysctl   416452 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac8d5d9 --prefix=/net/ipv4/neigh/vethac8d5d9 --prefix=/net/ipv6/conf/vethac8d5d9 --prefix=/net/ipv6/neigh/vethac8d5d9\n17.610  containerd-shim  416457 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa2 delete\n17.612  runc             416464 416457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2f --log-format json delete --force d560877d0c9b9af1b7993b8a66e92ef98a3ba693a20b72ed5c133283aa23b2fa\n17.649  systemd-sysctl   416469 416001   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a2351a --prefix=/net/ipv4/neigh/veth3a2351a --prefix=/net/ipv6/conf/veth3a2351a --prefix=/net/ipv6/neigh/veth3a2351a\n17.650  systemd-sysctl   416470 415998   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethed35d5c --prefix=/net/ipv4/neigh/vethed35d5c --prefix=/net/ipv6/conf/vethed35d5c --prefix=/net/ipv6/neigh/vethed35d5c\n17.786  runc             416471 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process1390342900 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n17.791  exe              416479 416471   0 /proc/self/exe init\n17.812  etcdctl          416481 416471   0 /usr/local/bin/etcdctl endpoint health\n18.042  cargo            416494 416234   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.053  cargo            416495 416270   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.057  rustc            416496 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.066  rustc            416498 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.099  rustc            416513 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.100  rustc            416514 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.101  rustc            416518 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=4400a25aaf223f04 ...\n18.102  rustc            416516 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=f2162428cb92f352 ...\n18.104  rustc            416519 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=e61b9f04f0d50a75 ...\n18.104  rustc            416520 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.104  rustc            416521 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.107  rustc            416517 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=1a810a4b3f0efeb6 ...\n18.242  cc               416576 416513   0 /tmp/native-trace-416270-1783994395653/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcEIgHYR/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.243  cc               416578 416576   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcEIgHYR/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.245  cc               416577 416514   0 /tmp/native-trace-416234-1783994395612/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcFfMWUc/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.247  cc               416579 416577   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcFfMWUc/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n18.248  collect2         416580 416578   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  collect2         416583 416579   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.250  ld.lld           416582 416580   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n18.253  ld.lld           416584 416583   0 \n18.253  rust-lld         416582 416580   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxfe4zT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.255  rust-lld         416584 416583   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cczdtA8W.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.257  sh               416586 2147557   0 /bin/sh -c which ps\n18.259  which            416586 2147557   0 /usr/bin/which ps\n18.262  sh               416587 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.264  ps               416587 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.294  rustc            416621 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"debug\", \"pool\", \"proptest\", \"quickcheck\", \"rayon\", \"refpool\", \"serde\")) -C metadata=1984f889580b2e34 ...\n18.298  rustc            416623 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"debug\", \"pool\", \"proptest\", \"quickcheck\", \"rayon\", \"refpool\", \"serde\")) -C metadata=1984f889580b2e34 ...\n18.300  sh               416624 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.302  cpuUsage.sh      416624 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.303  sed              416625 416624   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.306  cat              416629 416624   0 /usr/bin/cat /proc/2240539/stat\n18.308  cat              416630 416624   0 /usr/bin/cat /proc/4193716/stat\n18.310  sleep            416631 416624   0 /usr/bin/sleep 1\n18.324  build-script-bu  416637 416494   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n18.325  build-script-bu  416638 416495   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n18.327  rustc            416639 416638   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.327  rustc            416640 416637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.346  rustc            416658 416495   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.347  rustc            416656 416494   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.356  cc               416675 416621   0 /tmp/native-trace-416270-1783994395653/shims/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustc0NYk8i/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.1hodkv8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.358  cc               416682 416675   0 /usr/bin/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustc0NYk8i/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.1hodkv8.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.1hodkv8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.359  cargo            416683 416208   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.361  collect2         416685 416682   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.362  cc               416684 416623   0 /tmp/native-trace-416234-1783994395612/shims/cc -m64 /target/debug/build/im-rc-8dc1db58054b3257/rustcsDKD2Z/symbols.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.1cgo2vg9r2msirmqz4s24o733.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.29ctd0dn7lv9dsr3jsiq12pcv.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.377bv5j4qzn2k4166d3qth035.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.38zs488y8zxmwejlgltwzj0ht.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.48k373gaymus0ekhk4rf9lzao.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.69g9f5lurm0jst2d8z06t5ojn.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.7z0vs9la48tkg87khlognv2rk.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.88688yp9xxaztop71mjobj93o.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.cgozbi9ej1ptr9uzdqht5f1pe.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.e6cii7df25k6ncosjhvvs7rmr.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.etir814pq7fxkxnetsci2lxry.0bp0ikg.rcgu.o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257.0av81p54qop5cepdr1pkirxve.0bp0ikg.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n18.364  cc               416686 416684   0 \n18.364  ld.lld           416687 416685   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257 ...\n18.366  rust-lld         416687 416685   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjRsGcL.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.367  collect2         416688 416686   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.370  ld.lld           416689 416688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/im-rc-8dc1db58054b3257/build_script_build-8dc1db58054b3257 ...\n18.372  rust-lld         416689 416688   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccKgkYP0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.379  rustc            416690 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.405  cross            416726 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n18.406  rustc            416729 416726   0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.413  rustc            416729 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.420  rustc            416745 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name version_check --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=de4e2c29a5a03308 ...\n18.420  rustc            416742 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.423  rustc            416744 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cfg_if --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"core\", \"rustc-dep-of-std\")) -C metadata=ef45cdee1882644b ...\n18.428  rustc            416746 416683   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typenum --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typenum-1.20.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"const-generics\", \"i128\", \"scale-info\", \"scale_info\", \"strict\")) -C metadata=d8ce8a727baff604 ...\n18.429  rustc            416750 416726   0 /home/xmoe/.cargo/bin/rustc -vV\n18.437  rustc            416750 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.438  build-script-bu  416769 416495   0 /target/debug/build/im-rc-8dc1db58054b3257/build-script-build\n18.442  rustc            416770 416769   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n18.451  cargo            416778 416726   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.456  build-script-bu  416789 416494   0 /target/debug/build/im-rc-8dc1db58054b3257/build-script-build\n18.458  cargo            416778 416726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.460  rustc            416790 416789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n"
    },
    {
      "argv": [
        "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build",
      "pid": 412173,
      "ppid": 411794,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/3020265423487988854detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 412176,
      "ppid": 412173,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/3020265423487988854detect_compiler_family.c",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 412178,
      "ppid": 412176,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 412186,
      "ppid": 412173,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-Wall",
        "-Wextra",
        "-march=armv8-a+crypto",
        "-c",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
        "-c",
        "src/sha256_aarch64.S"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-gcc",
      "pid": 412201,
      "ppid": 412173,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
        "-E",
        "-lang-asm",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "src/sha256_aarch64.S",
        "-march=armv8-a+crypto",
        "-mlittle-endian",
        "-mabi=lp64",
        "-Wall",
        "-Wextra",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-fno-omit-frame-pointer",
        "-g",
        "-gdwarf-4",
        "-fworking-directory",
        "-O0",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1",
      "pid": 412202,
      "ppid": 412201,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "--gdwarf2",
        "-EL",
        "-march=armv8-a+crypto",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o",
        "/tmp/ccJ6QezS.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 412209,
      "ppid": 412201,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/81a71fbc30f7fcce-sha256_aarch64.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 412231,
      "ppid": 412173,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/sha2-asm-d5314d395257e804/out/libsha256.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 412173,
      "build_script_target_dir": "sha2-asm-e0eb8c965c490186",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 412235,
      "ppid": 412173,
      "root_cargo_pid": 411794,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "sha2-asm",
      "cwd": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "event_id": "bsrun:dacd6b7cde7481e1:1030ac0be42b35c9:ba0670e4edc2a9ee",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/sha2-asm-e0eb8c965c490186/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
      "out_dir": "/target/debug/build/sha2-asm-e0eb8c965c490186/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
      "success": true,
      "target": null,
      "version": "0.6.4",
      "_owner": {
        "crate": "sha2-asm",
        "version": "0.6.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4#sha2-asm@0.6.4",
        "manifest_dir": "/tmp/crate-build-aarch64-qu3671jv/src/sha2-asm-0.6.4",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1755,
    "crate": "sha2-asm",
    "version": "0.6.4",
    "crate_id": "13586",
    "version_id": "1137185",
    "downloads": 9024300,
    "cumulative_downloads": 99772145716,
    "cumulative_share_of_global": 0.3730250198520934,
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
