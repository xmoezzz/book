# `dlmalloc` `0.2.4`

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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
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
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
    "/target/debug/build/dlmalloc-e249455d30ed6cef",
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
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-573661-1783994811471967261.map",
  "pid": 573661,
  "ppid": 573572,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-573661-1783994811471967261.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
      "name": "dlmalloc",
      "version": "0.2.4",
      "manifest_path": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fuchsia-cprng@0.1.1",
      "name": "fuchsia-cprng",
      "version": "0.1.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.3.23",
      "name": "rand",
      "version": "0.3.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.4.6",
      "name": "rand",
      "version": "0.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.3.1",
      "name": "rand_core",
      "version": "0.3.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
      "name": "rand_core",
      "version": "0.4.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rdrand@0.4.0",
      "name": "rdrand",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
      "name": "winapi",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
      "name": "winapi-i686-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
    }
  ],
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 573661,
  "ppid": 573572,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:c3ad813d23dc48b5:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
  "pid": 573661,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:6752c8338668d6e6:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "2602a12336cf81bde7b0d3c60160cef530c5ec2c772dc19b3725e8559f8a83c8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:575ad4c66c3e88d4:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "92888cff827bed4b7df8c9c7a42b86fbecf5c10a5fc4bdf2ef2a927eb4749225",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:9807fb4463b7c9c6:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "f100e4daa6d126f837eef6d4397dedd4611400be4fd18d1bedfb94c4d3cfb08b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:8a786129fd96f7c7:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "13d34274b1ee30ccb9f652b59ea94000b82bd10c47807b4f15f008591adbc864",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:bd515eab5dc87029:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "fe90983281f3185c47f02ac0bf7a88d3e2863aa4b5672561381d4bcafbabaaf9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "used:cc:8febff4878ce6109:be23be1e5b8c9498:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
  "pid": 573661,
  "sha256": "3b90de6ca03bdb1dce7647a1029cfc8bae30bfaf1c888b94a655900fd9aa28f8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
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
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "context_path": "/tmp/native-trace-571788-1783994806720/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-571788-1783994806720/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 573661,
  "ppid": 573572,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
    "/target/debug/build/dlmalloc-e249455d30ed6cef",
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
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-573661-1783994811471967261.map",
  "pid": 573661,
  "ppid": 573572,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-573661-1783994811471967261.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 573846,
  "ppid": 573560,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:8900b2156fd8c763:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
  "pid": 573846,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
  "pid": 573846,
  "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
  "pid": 573846,
  "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
  "pid": 573846,
  "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 18

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
  "pid": 573846,
  "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
  "pid": 573846,
  "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
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
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 21

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "/tmp/native-trace-571788-1783994806720/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-571788-1783994806720/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 573846,
  "ppid": 573560,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 22

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw",
    "/target/debug/build/libc-8a22300c8f78b6db",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a22300c8f78b6db",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-573846-1783994811741105716.map",
  "pid": 573846,
  "ppid": 573560,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-573846-1783994811741105716.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

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

#### Record 24

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 4324,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 4325,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "87ba787ca8bac826b9a7cd5e92f0b55303f1312c\n19.117  touch            580477 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-cmeth_lib.d.tmp\n19.128  as               580483 580009   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-p_verify.o /tmp/ccdUCDsL.s\n19.130  aarch64-linux-g  580476 580464   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.130  sh               580482 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.137  cc1              580485 580476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hashtable/libcrypto-lib-hashfunc.d -MF crypto/hashtable/libcrypto-lib-hashfunc.d.tmp -MQ crypto/hashtable/libcrypto-lib-hashfunc.o -D_REENTRANT -D ...\n19.144  cmp              580484 580482   0 /usr/bin/cmp crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d\n19.153  mv               580488 580482   0 /usr/bin/mv crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d\n19.156  sh               580486 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.158  as               580489 579834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_ossl.o /tmp/ccMFCsoX.s ...\n19.158  sh               580487 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.161  as               580490 580081   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dso/libcrypto-lib-dso_win32.o /tmp/cc8hIOQW.s ...\n19.161  riscv64-linux-g  580494 580487   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.162  build-script-bu  580495 576080   0 /target/debug/build/android-activity-cf828d8ea559b7fe/build-script-build\n19.163  sh               580492 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DEC\n19.167  touch            580499 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp\n19.168  as               580496 580077   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-dsa_ctrl.o /tmp/cckcf72S.s\n19.171  sh               580500 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d > /dev/null 2> /dev/nul\n19.171  cc1              580497 580494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_ameth.d -MF crypto/ec/libcrypto-lib-ec_ameth.d.tmp -MQ crypto/ec/libcrypto-lib-ec_ameth.o ...\n19.175  cmp              580504 580500   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d\n19.177  powerpc64le-lin  580498 580492   0 /usr/bin/powerpc64le-linux-gnu-gcc -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread ...\n19.180  systemd-sysctl   580508 580342   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaab3ea9 --prefix=/net/ipv4/neigh/vethaab3ea9 --prefix=/net/ipv6/conf/vethaab3ea9 --prefix=/net/ipv6/neigh/vethaab3ea9\n19.181  rustc            580505 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name jni_sys_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-sys-macros-0.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n19.181  rustc            580506 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n19.181  rustc            580507 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_enum_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum_derive-0.7.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro-crate\" --cfg feature=\"std\" ...\n19.194  mv               580509 580500   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d\n19.195  as               580514 579796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_lib.o /tmp/ccBrdDHu.s ...\n19.203  sh               580520 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.203  cmp              580491 580486   0 /usr/bin/cmp crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d\n19.205  touch            580521 567660   0 /usr/bin/touch crypto/dso/libcrypto-lib-dso_win32.d.tmp\n19.217  powerpc64le-lin  580524 580520   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.219  as               580523 580476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/hashtable/libcrypto-lib-hashfunc.o /tmp/cc8m54n4.s\n19.219  cc1              580522 580498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I crypto -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_des3.d -MF crypto/evp/libcrypto-lib-e_des3.d.tmp -MQ crypto/evp/libcrypto-lib-e_des3.o ...\n19.233  sh               580525 567660   0 /bin/sh -c if cmp crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.236  touch            580529 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_lib.d.tmp\n19.236  touch            580531 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-p_verify.d.tmp\n19.237  touch            580532 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp\n19.238  sh               580533 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.240  cmp              580536 580525   0 /usr/bin/cmp crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d\n19.242  as               580528 580046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dso/libcrypto-lib-dso_lib.o /tmp/ccC65t6W.s ...\n19.243  cc1              580530 580524   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_idea.d -MF crypto/evp/libcrypto-lib-e_idea.d.tmp -MQ crypto/evp/libcrypto-lib-e_idea.o -D_REENTRANT -D ...\n19.245  mv               580538 580525   0 /usr/bin/mv crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d\n19.245  sh               580535 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.246  cmp              580537 580533   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d\n19.247  as               580534 580215   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-curve448_tables.o /tmp/ccsuM5UA.s ...\n19.254  touch            580526 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp\n19.256  mv               580541 580533   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d\n19.256  sed              580542 580160   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.260  cat              580543 580160   0 \n19.262  cat              580546 580160   0 /usr/bin/cat /proc/4193716/stat\n19.266  sh               580539 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.268  sh               580548 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.268  sh               580551 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.273  sh               580550 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.273  cmp              580549 580539   0 /usr/bin/cmp crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d\n19.280  touch            580552 564020   0 /usr/bin/touch crypto/hashtable/libcrypto-lib-hashfunc.d.tmp\n19.284  riscv64-linux-g  580553 580550   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.285  riscv64-linux-g  580554 580548   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.289  cmp              580556 580551   0 /usr/bin/cmp crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d\n19.291  mv               580559 580551   0 /usr/bin/mv crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d\n19.294  mv               580555 580539   0 /usr/bin/mv crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d\n19.294  containerd-shim  580544 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1051b837fec7188901764199513ccaf096950ed74bff371ed7e081beb8f96a4b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1051b837fec7188901764199513ccaf096950ed74bff371ed7e081beb8f delete\n19.294  mv               580527 580486   0 /usr/bin/mv crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d\n19.297  runc             580565 580544   0 \n19.297  touch            580558 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp\n19.299  touch            580566 567660   0 /usr/bin/touch crypto/dso/libcrypto-lib-dso_lib.d.tmp\n19.299  sh               580557 564020   0 /bin/sh -c if cmp crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d > /dev/null 2> /dev/null; then \\\\n\n19.304  sh               580575 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d > /dev/null 2> \n19.304  sh               580578 567660   0 /bin/sh -c if cmp crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.304  cc1              580576 580554   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_asn1.d -MF crypto/ec/libcrypto-lib-ec_asn1.d.tmp -MQ crypto/ec/libcrypto-lib-ec_asn1.o ...\n19.306  cmp              580580 580578   0 /usr/bin/cmp crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d\n19.308  cmp              580572 580557   0 /usr/bin/cmp crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d\n19.309  mv               580582 580578   0 /usr/bin/mv crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d\n19.313  sh               580581 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.314  cc1              580574 580553   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_backend.d -MF crypto/ec/libcrypto-lib-ec_backend.d.tmp -MQ crypto/ec/libcrypto-lib-ec_backend.o ...\n19.316  cmp              580579 580575   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d\n19.318  rustc            580577 576007   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"game-activity\", \"native-activity\")) ...\n19.326  as               580586 580197   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.o /tmp/ccPfHTdY.s\n19.328  aarch64-linux-g  580583 580581   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.329  mv               580584 580557   0 /usr/bin/mv crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d\n19.341  cc1              580588 580583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hashtable/libcrypto-lib-hashtable.d -MF crypto/hashtable/libcrypto-lib-hashtable.d.tmp -MQ crypto/hashtable/libcrypto-lib-hashtable.o -D_REENTRANT -D ...\n19.343  as               580589 580111   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.o /tmp/ccn5Rovu.s\n19.348  sh               580587 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.358  powerpc64le-lin  580596 580587   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.362  sh               580598 580342   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7348059\n19.363  cc1              580599 580596   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_null.d -MF crypto/evp/libcrypto-lib-e_null.d.tmp -MQ crypto/evp/libcrypto-lib-e_null.o -D_REENTRANT -D ...\n19.364  sed              580602 580598   0 /usr/bin/sed -n s/^driver: //p\n19.365  as               580600 580283   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-skeymgmt_meth.o /tmp/ccuHVopt.s\n19.368  ethtool          580601 580598   0 /usr/sbin/ethtool -i veth7348059\n19.372  sh               580595 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.373  touch            580603 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp\n19.378  aarch64-linux-g  580606 580595   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.379  mv               580585 580575   0 /usr/bin/mv crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d\n19.379  touch            580607 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp\n19.380  sh               580593 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.380  sh               580608 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d > /dev/null 2> /dev/nul\n19.382  systemd-sysctl   580609 580342   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7348059 --prefix=/net/ipv4/neigh/veth7348059 --prefix=/net/ipv6/conf/veth7348059 --prefix=/net/ipv6/neigh/veth7348059\n19.382  sh               580610 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d > /dev/null 2> /dev\n19.385  cmp              580613 580610   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d\n19.390  riscv64-linux-g  580612 580593   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.391  cc1              580616 580606   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hmac/libcrypto-lib-hmac.d -MF crypto/hmac/libcrypto-lib-hmac.d.tmp -MQ crypto/hmac/libcrypto-lib-hmac.o -D_REENTRANT -D ...\n19.394  cmp              580540 580535   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d\n19.394  cmp              580611 580608   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d\n19.397  sh               580619 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.408  mv               580618 580610   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d\n19.408  powerpc64le-lin  580622 580619   0 \n19.410  cc1              580625 580622   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_old.d -MF crypto/evp/libcrypto-lib-e_old.d.tmp -MQ crypto/evp/libcrypto-lib-e_old.o -D_REENTRANT -D ...\n19.414  mv               580621 580608   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d\n19.414  cc1              580617 580612   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_check.d -MF crypto/ec/libcrypto-lib-ec_check.d.tmp -MQ crypto/ec/libcrypto-lib-ec_check.o ...\n19.417  as               580624 580524   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_idea.o /tmp/cc0HyC7G.s\n19.422  touch            580626 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp\n19.434  sh               580627 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d > /dev/null 2> /dev/null; then \\\\n\tr\n19.440  as               580629 580261   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-f_generic.o /tmp/ccqHqa8P.s ...\n19.443  cmp              580628 580627   0 /usr/bin/cmp crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d\n19.457  sh               580637 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.464  powerpc64le-lin  580638 580637   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.469  mv               580639 580627   0 /usr/bin/mv crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d\n19.478  cc1              580641 580638   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc2.d -MF crypto/evp/libcrypto-lib-e_rc2.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc2.o -D_REENTRANT -D ...\n19.479  sh               580642 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.489  sh               580620 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.489  cc               580644 580577   0 /tmp/native-trace-574409-1783994812229/shims/cc -m64 /target/debug/build/android-activity-cf828d8ea559b7fe/rustcJ9byMS/symbols.o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.137yricpsumo729ibuhzl8j30.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.4izw380gqeii70j45vths6l1n.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8gl0knciminbylk71sqi0vobx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8uysvnewy5ac2mdanfvsi1ztx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.akwjjg0cjn8p2u7393d809f07.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.21xajqu33kzjkykxk9l4ij2ek.19pcfm5.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-56811999bf1868bb.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libjobserver-d7000c5cfc455764.rlib /target/debug/deps/liblibc-32a9bea892533c7a.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n19.492  aarch64-linux-g  580643 580642   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.492  cc               580646 580644   0 /usr/bin/cc -m64 /target/debug/build/android-activity-cf828d8ea559b7fe/rustcJ9byMS/symbols.o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.137yricpsumo729ibuhzl8j30.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.4izw380gqeii70j45vths6l1n.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8gl0knciminbylk71sqi0vobx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8uysvnewy5ac2mdanfvsi1ztx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.akwjjg0cjn8p2u7393d809f07.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.21xajqu33kzjkykxk9l4ij2ek.19pcfm5.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-56811999bf1868bb.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libjobserver-d7000c5cfc455764.rlib /target/debug/deps/liblibc-32a9bea892533c7a.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n19.495  collect2         580647 580646   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.501  ld.lld           580650 580647   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe ...\n19.501  cc1              580649 580643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hpke/libcrypto-lib-hpke.d -MF crypto/hpke/libcrypto-lib-hpke.d.tmp -MQ crypto/hpke/libcrypto-lib-hpke.o -D_REENTRANT -D ...\n19.501  touch            580648 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp\n19.506  sh               580652 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d > /dev/null 2> /dev/null; t\n19.508  cmp              580653 580652   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d\n19.508  sh               580640 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.510  riscv64-linux-g  580651 580620   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.514  mv               580655 580652   0 /usr/bin/mv crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d\n19.520  rust-lld         580650 580647   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.520  powerpc64le-lin  580654 580640   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.526  sh               580657 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.529  cc1              580656 580651   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_curve.d -MF crypto/ec/libcrypto-lib-ec_curve.d.tmp -MQ crypto/ec/libcrypto-lib-ec_curve.o ...\n19.533  cc1              580658 580654   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc4.d -MF crypto/evp/libcrypto-lib-e_rc4.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc4.o -D_REENTRANT -D ...\n19.533  mv               580645 580535   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d\n19.536  riscv64-linux-g  580660 580657   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.537  touch            580659 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_idea.d.tmp\n19.538  sh               580661 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.543  riscv64-linux-g  580662 580661   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.545  cc1              580663 580660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_cvt.d -MF crypto/ec/libcrypto-lib-ec_cvt.d.tmp -MQ crypto/ec/libcrypto-lib-ec_cvt.o ...\n19.546  cc1              580664 580662   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_deprecated.d -MF crypto/ec/libcrypto-lib-ec_deprecated.d.tmp -MQ crypto/ec/libcrypto-lib-ec_deprecated.o ...\n19.553  as               580665 580280   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_cast.o /tmp/cc06IJbh.s\n19.562  as               580667 580255   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-signature.o /tmp/cccoJEBl.s\n19.565  sh               580666 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.570  as               580669 580288   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_backend.o /tmp/ccWFwJ7S.s\n19.591  as               580670 579538   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_ameth.o /tmp/cca0ay8F.s ...\n19.602  touch            580671 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_cast.d.tmp\n19.607  cmp              580668 580666   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d\n19.622  touch            580690 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp\n19.627  sh               580689 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.631  cmp              580691 580689   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d\n19.638  sh               580692 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.640  mv               580693 580666   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d\n19.648  cmp              580694 580692   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d\n19.648  mv               580695 580689   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d\n19.650  as               580696 580350   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_dh.o /tmp/cc3Fg3Ox.s\n19.657  mv               580697 580692   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d\n19.658  sh               580698 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.663  sh               580699 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.665  powerpc64le-lin  580700 580698   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.669  riscv64-linux-g  580702 580699   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.670  cc1              580701 580700   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc4_hmac_md5.d -MF crypto/evp/libcrypto-lib-e_rc4_hmac_md5.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc4_hmac_md5.o -D_REENTRANT -D ...\n19.682  sh               580703 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.685  powerpc64le-lin  580705 580703   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.688  cc1              580704 580702   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_err.d -MF crypto/ec/libcrypto-lib-ec_err.d.tmp -MQ crypto/ec/libcrypto-lib-ec_err.o ...\n19.693  cc1              580707 580705   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc5.d -MF crypto/evp/libcrypto-lib-e_rc5.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc5.o -D_REENTRANT -D ...\n19.711  touch            580688 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_backend.d.tmp\n19.712  as               580706 580612   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_check.o /tmp/ccKkJa2f.s ...\n19.714  build-script-bu  580709 576007   0 /target/debug/build/android-activity-cf828d8ea559b7fe/build-script-build\n19.723  sh               580710 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n19.723  as               580711 580157   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.o /tmp/ccQmGwp4.s ...\n19.743  touch            580713 567660   0 /usr/bin/touch crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp\n19.746  cmp              580712 580710   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d\n19.750  sh               580715 567660   0 /bin/sh -c if cmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d > /dev/null 2\n19.750  as               580714 580660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_cvt.o /tmp/ccpA3CXe.s ...\n19.756  cmp              580716 580715   0 /usr/bin/cmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d\n19.757  mv               580717 580710   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d\n19.762  touch            580719 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-signature.d.tmp\n19.764  sh               580720 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.766  as               580721 580662   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_deprecated.o /tmp/cch5XHMR.s ...\n19.768  as               580718 580388   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_key_validate.o /tmp/ccdr1Bfp.s\n19.769  aarch64-linux-g  580722 580720   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.771  as               580725 580596   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_null.o /tmp/ccF6KjY8.s\n19.774  sh               580723 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-signature.d.tmp crypto/evp/libcrypto-lib-signature.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.775  cc1              580726 580722   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hpke/libcrypto-lib-hpke_util.d -MF crypto/hpke/libcrypto-lib-hpke_util.d.tmp -MQ crypto/hpke/libcrypto-lib-hpke_util.o -D_REENTRANT -D ...\n19.775  mv               580727 580715   0 /usr/bin/mv crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d\n19.790  cmp              580729 580723   0 \n19.790  mv               580734 580723   0 /usr/bin/mv crypto/evp/libcrypto-lib-signature.d.tmp crypto/evp/libcrypto-lib-signature.d\n19.790  touch            580724 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_check.d.tmp\n19.790  cmp              580732 580730   0 \n19.790  touch            580728 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_deprecated.d.tmp\n19.790  sh               580730 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_check.d.tmp crypto/ec/libcrypto-lib-ec_check.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.790  sh               580731 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d > /dev/null 2> /dev/null; then \\\\n\trm \n19.790  cmp              580733 580731   0 /usr/bin/cmp crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d\n19.790  mv               580735 580731   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d\n19.792  sh               580736 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.795  riscv64-linux-g  580739 580736   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.795  mv               580737 580730   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_check.d.tmp crypto/ec/libcrypto-lib-ec_check.d\n19.799  sh               580738 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.802  cc1              580740 580739   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_key.d -MF crypto/ec/libcrypto-lib-ec_key.d.tmp -MQ crypto/ec/libcrypto-lib-ec_key.o ...\n19.812  touch            580742 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_dh.d.tmp\n19.813  touch            580741 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_cvt.d.tmp\n19.816  sh               580745 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.818  riscv64-linux-g  580746 580745   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.820  riscv64-linux-g  580743 580738   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.821  cc1              580747 580746   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_lib.d -MF crypto/ec/libcrypto-lib-ec_lib.d.tmp -MQ crypto/ec/libcrypto-lib-ec_lib.o ...\n19.824  sh               580748 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ec/l\n19.830  cc1              580749 580743   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_kmeth.d -MF crypto/ec/libcrypto-lib-ec_kmeth.d.tmp -MQ crypto/ec/libcrypto-lib-ec_kmeth.o ...\n19.832  cmp              580750 580748   0 /usr/bin/cmp crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d\n19.838  sh               580744 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.840  touch            580751 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_null.d.tmp\n19.843  sh               580752 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ff\n19.843  aarch64-linux-g  580754 580744   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.854  cmp              580756 580752   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d\n19.857  cc1              580757 580754   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_client.d -MF crypto/http/libcrypto-lib-http_client.d.tmp -MQ crypto/http/libcrypto-lib-http_client.o -D_REENTRANT -D ...\n19.861  as               580758 580397   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_key_generate.o /tmp/cc9ALil6.s\n19.875  mv               580755 580748   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d\n19.875  git              580759 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n19.876  mv               580760 580752   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d\n19.897  touch            580764 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp\n19.898  sh               580765 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d > /dev/null 2> /dev/null; the\n19.899  sh               580766 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.901  as               580763 579714   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-bio_b64.o /tmp/ccTYeAHq.s\n19.904  cmp              580767 580765   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d\n19.907  sh               580770 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.911  mv               580769 580765   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d\n19.911  aarch64-linux-g  580771 580770   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.915  cc1              580774 580771   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_err.d -MF crypto/http/libcrypto-lib-http_err.d.tmp -MQ crypto/http/libcrypto-lib-http_err.o -D_REENTRANT -D ...\n19.923  riscv64-linux-g  580768 580766   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.941  sh               580753 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.943  cmp              580776 580753   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d\n19.945  touch            580777 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp\n19.946  sh               580778 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d > /dev/null 2> /dev/null; the\n19.948  mv               580780 580753   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d\n19.949  cmp              580779 580778   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d\n19.952  sh               580781 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -Icrypto -Icrypto/modes -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include \n19.957  powerpc64le-lin  580782 580781   0 /usr/bin/powerpc64le-linux-gnu-gcc -Icrypto -Icrypto/modes -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC ...\n19.959  cc1              580775 580768   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_mult.d -MF crypto/ec/libcrypto-lib-ec_mult.d.tmp -MQ crypto/ec/libcrypto-lib-ec_mult.o ...\n19.962  cc1              580783 580782   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I crypto -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_sm4.d -MF crypto/evp/libcrypto-lib-e_sm4.d.tmp ...\n19.970  mv               580786 580778   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d\n19.986  sh               580784 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.990  sh               580788 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.990  aarch64-linux-g  580787 580784   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.994  aarch64-linux-g  580789 580788   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n20.004  cc1              580790 580787   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_lib.d -MF crypto/http/libcrypto-lib-http_lib.d.tmp -MQ crypto/http/libcrypto-lib-http_lib.o -D_REENTRANT -D ...\n20.007  cc1              580792 580789   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/kdf/libcrypto-lib-kdf_err.d -MF crypto/kdf/libcrypto-lib-kdf_err.d.tmp -MQ crypto/kdf/libcrypto-lib-kdf_err.o -D_REENTRANT -D ...\n20.021  as               580794 580771   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/http/libcrypto-lib-http_err.o /tmp/cc34MGPl.s\n20.052  touch            580797 564020   0 /usr/bin/touch crypto/http/libcrypto-lib-http_err.d.tmp\n20.059  sh               580798 564020   0 /bin/sh -c if cmp crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n20.060  as               580793 580638   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_rc2.o /tmp/cczbhKVh.s\n20.071  cmp              580799 580798   0 /usr/bin/cmp crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d\n20.075  touch            580800 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-bio_b64.d.tmp\n20.081  touch            580801 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_rc2.d.tmp\n20.085  mv               580804 580798   0 /usr/bin/mv crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d\n20.085  sh               580803 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n20.085  as               580802 580321   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-scalar.o /tmp/ccH3uRkm.s ...\n20.090  cmp              580806 580803   0 /usr/bin/cmp crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d\n20.095  sh               580807 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n20.102  sh               580805 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/evp/\n20.111  aarch64-linux-g  580808 580807   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n20.122  mv               580812 580803   0 /usr/bin/mv crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d\n20.135  cmp              580810 580805   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d\n20.136  cc1              580813 580808   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/lhash/libcrypto-lib-lh_stats.d -MF crypto/lhash/libcrypto-lib-lh_stats.d.tmp -MQ crypto/lhash/libcrypto-lib-lh_stats.o -D_REENTRANT -D ...\n20.142  touch            580814 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-scalar.d.tmp\n20.142  as               580815 580123   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-pmeth_check.o /tmp/ccBX8USm.s\n20.145  mv               580817 580805   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d\n20.154  sh               580818 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n20.154  sh               580816 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-scalar.d.tmp crypto/ec/curve448/libcrypto-lib-scalar.d > /dev/null 2> /dev/null; then \\\\n\n20.160  cmp              580819 580816   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-scalar.d.tmp crypto/ec/curve448/libcrypto-lib-scalar.d\n20.162  powerpc64le-lin  580820 580818   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n20.166  sh               580822 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n20.170  powerpc64le-lin  580823 580822   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n20.171  cc1              580824 580820   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_xcbc_d.d -MF crypto/evp/libcrypto-lib-e_xcbc_d.d.tmp -MQ crypto/evp/libcrypto-lib-e_xcbc_d.o -D_REENTRANT -D ...\n20.177  cc1              580825 580823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-ec_ctrl.d -MF crypto/evp/libcrypto-lib-ec_ctrl.d.tmp -MQ crypto/evp/libcrypto-lib-ec_ctrl.o -D_REENTRANT -D ...\n20.231  as               580828 580244   0 \n20.251  as               580830 579931   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-dh_ctrl.o /tmp/ccTD0f2P.s\n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 573764,
  "build_script_target_dir": "dlmalloc-e249455d30ed6cef",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
  "pid": 573764,
  "ppid": 573410,
  "root_cargo_pid": 573410,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "_build_script_out_dir": "/target/debug/build/dlmalloc-e249455d30ed6cef/out"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 574135,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 574135,
  "ppid": 573410,
  "root_cargo_pid": 573410,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 574135,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 574152,
  "ppid": 574135,
  "root_cargo_pid": 573410,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "crate": "dlmalloc",
  "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "event_id": "bsrun:b277b3f0917962c5:8de3aa913df56e91:cbf50263c00d1646",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
  "out_dir": "/target/debug/build/dlmalloc-e249455d30ed6cef/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
  "success": true,
  "target": null,
  "version": "0.2.4",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
    "source": "cwd_prefix"
  }
}
```

#### Record 29

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
  "success": true,
  "target": null,
  "version": "0.2.186",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 574135,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 574152,
  "ppid": 574135,
  "root_cargo_pid": 573410,
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
  "time": "2026-07-14T02:07:11.986395+00:00",
  "crate": "dlmalloc",
  "version": "0.2.4",
  "architecture": "aarch64",
  "duration_seconds": 32.54862202098593,
  "trace_record_count": 29,
  "trace_owner_summary": {
    "owner_package_count": 11,
    "owner_packages": [
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "fuchsia-cprng",
        "version": "0.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fuchsia-cprng@0.1.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.3.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.4.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "rdrand",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rdrand@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.3.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.3.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6/Cargo.toml"
      },
      {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "manifest_path": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 24,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "dlmalloc",
        "version": "0.2.4",
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
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "event_count": 11,
        "kind_counts": {
          "exec": 1,
          "used_input": 6,
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
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
          "name": "dlmalloc",
          "version": "0.2.4",
          "manifest_path": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fuchsia-cprng@0.1.1",
          "name": "fuchsia-cprng",
          "version": "0.1.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fuchsia-cprng-0.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.3.23",
          "name": "rand",
          "version": "0.3.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.4.6",
          "name": "rand",
          "version": "0.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.3.1",
          "name": "rand_core",
          "version": "0.3.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.4.2",
          "name": "rand_core",
          "version": "0.4.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.4.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rdrand@0.4.0",
          "name": "rdrand",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rdrand-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
          "name": "winapi",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
          "name": "winapi-i686-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
        }
      ],
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 573661,
      "ppid": 573572,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:c3ad813d23dc48b5:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
      "pid": 573661,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:6752c8338668d6e6:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "2602a12336cf81bde7b0d3c60160cef530c5ec2c772dc19b3725e8559f8a83c8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:575ad4c66c3e88d4:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "92888cff827bed4b7df8c9c7a42b86fbecf5c10a5fc4bdf2ef2a927eb4749225",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:9807fb4463b7c9c6:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "f100e4daa6d126f837eef6d4397dedd4611400be4fd18d1bedfb94c4d3cfb08b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:8a786129fd96f7c7:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "13d34274b1ee30ccb9f652b59ea94000b82bd10c47807b4f15f008591adbc864",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:bd515eab5dc87029:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "fe90983281f3185c47f02ac0bf7a88d3e2863aa4b5672561381d4bcafbabaaf9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "used:cc:8febff4878ce6109:be23be1e5b8c9498:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
      "pid": 573661,
      "sha256": "3b90de6ca03bdb1dce7647a1029cfc8bae30bfaf1c888b94a655900fd9aa28f8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
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
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "context_path": "/tmp/native-trace-571788-1783994806720/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-571788-1783994806720/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 573661,
      "ppid": 573572,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
        "/target/debug/build/dlmalloc-e249455d30ed6cef",
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
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustc7Vd4nF/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.0wuv0nr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.0wuv0nr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.0wuv0nr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.0wuv0nr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.0wuv0nr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.0wuv0nr.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-573661-1783994811471967261.map",
      "pid": 573661,
      "ppid": 573572,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-573661-1783994811471967261.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 573846,
      "ppid": 573560,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:8900b2156fd8c763:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
      "pid": 573846,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:c5eb16742d92300e:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
      "pid": 573846,
      "sha256": "750e5b687b769ef8e1f6a9de3b3b4cc39d771526f669d42b53a924666b856dae",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:135ba558c9da774d:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
      "pid": 573846,
      "sha256": "53140dc43536033138eb06a34e55a6a0ff33641d1e3937f2ad7a716aa3ee683a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:2a8f9787c6af6fe7:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
      "pid": 573846,
      "sha256": "d07a13370e4d6a6a6abdcfd76827ef7c0991362bd0043ae1f902898148c0a6fb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:e37cae5c272f2a12:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
      "pid": 573846,
      "sha256": "c1d04af73990d492aeddeae1678948453dcb03afe9564782fafda521716fd66f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:759cfb97b73257cf:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
      "pid": 573846,
      "sha256": "8ef6a5d57a020f215781ab0bc6a156213342dbd5f757c677fe270d0bad9c7795",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
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
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "/tmp/native-trace-571788-1783994806720/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-571788-1783994806720/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 573846,
      "ppid": 573560,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw",
        "/target/debug/build/libc-8a22300c8f78b6db",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustc0apONw/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a22300c8f78b6db",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-573846-1783994811741105716.map",
      "pid": 573846,
      "ppid": 573560,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-573846-1783994811741105716.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
      "parsed_event_count": 4324,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 4325,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "87ba787ca8bac826b9a7cd5e92f0b55303f1312c\n19.117  touch            580477 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-cmeth_lib.d.tmp\n19.128  as               580483 580009   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-p_verify.o /tmp/ccdUCDsL.s\n19.130  aarch64-linux-g  580476 580464   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.130  sh               580482 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.137  cc1              580485 580476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hashtable/libcrypto-lib-hashfunc.d -MF crypto/hashtable/libcrypto-lib-hashfunc.d.tmp -MQ crypto/hashtable/libcrypto-lib-hashfunc.o -D_REENTRANT -D ...\n19.144  cmp              580484 580482   0 /usr/bin/cmp crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d\n19.153  mv               580488 580482   0 /usr/bin/mv crypto/evp/libcrypto-lib-asymcipher.d.tmp crypto/evp/libcrypto-lib-asymcipher.d\n19.156  sh               580486 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.158  as               580489 579834   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_ossl.o /tmp/ccMFCsoX.s ...\n19.158  sh               580487 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.161  as               580490 580081   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dso/libcrypto-lib-dso_win32.o /tmp/cc8hIOQW.s ...\n19.161  riscv64-linux-g  580494 580487   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.162  build-script-bu  580495 576080   0 /target/debug/build/android-activity-cf828d8ea559b7fe/build-script-build\n19.163  sh               580492 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DEC\n19.167  touch            580499 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp\n19.168  as               580496 580077   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-dsa_ctrl.o /tmp/cckcf72S.s\n19.171  sh               580500 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d > /dev/null 2> /dev/nul\n19.171  cc1              580497 580494   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_ameth.d -MF crypto/ec/libcrypto-lib-ec_ameth.d.tmp -MQ crypto/ec/libcrypto-lib-ec_ameth.o ...\n19.175  cmp              580504 580500   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d\n19.177  powerpc64le-lin  580498 580492   0 /usr/bin/powerpc64le-linux-gnu-gcc -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread ...\n19.180  systemd-sysctl   580508 580342   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaab3ea9 --prefix=/net/ipv4/neigh/vethaab3ea9 --prefix=/net/ipv6/conf/vethaab3ea9 --prefix=/net/ipv6/neigh/vethaab3ea9\n19.181  rustc            580505 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name jni_sys_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/jni-sys-macros-0.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n19.181  rustc            580506 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n19.181  rustc            580507 573693   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_enum_derive --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num_enum_derive-0.7.6/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro-crate\" --cfg feature=\"std\" ...\n19.194  mv               580509 580500   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_chacha20_poly1305.d.tmp crypto/evp/libcrypto-lib-e_chacha20_poly1305.d\n19.195  as               580514 579796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_lib.o /tmp/ccBrdDHu.s ...\n19.203  sh               580520 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.203  cmp              580491 580486   0 /usr/bin/cmp crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d\n19.205  touch            580521 567660   0 /usr/bin/touch crypto/dso/libcrypto-lib-dso_win32.d.tmp\n19.217  powerpc64le-lin  580524 580520   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.219  as               580523 580476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/hashtable/libcrypto-lib-hashfunc.o /tmp/cc8m54n4.s\n19.219  cc1              580522 580498   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I crypto -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_des3.d -MF crypto/evp/libcrypto-lib-e_des3.d.tmp -MQ crypto/evp/libcrypto-lib-e_des3.o ...\n19.233  sh               580525 567660   0 /bin/sh -c if cmp crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.236  touch            580529 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_lib.d.tmp\n19.236  touch            580531 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-p_verify.d.tmp\n19.237  touch            580532 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp\n19.238  sh               580533 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.240  cmp              580536 580525   0 /usr/bin/cmp crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d\n19.242  as               580528 580046   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dso/libcrypto-lib-dso_lib.o /tmp/ccC65t6W.s ...\n19.243  cc1              580530 580524   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_idea.d -MF crypto/evp/libcrypto-lib-e_idea.d.tmp -MQ crypto/evp/libcrypto-lib-e_idea.o -D_REENTRANT -D ...\n19.245  mv               580538 580525   0 /usr/bin/mv crypto/dso/libcrypto-lib-dso_win32.d.tmp crypto/dso/libcrypto-lib-dso_win32.d\n19.245  sh               580535 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.246  cmp              580537 580533   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d\n19.247  as               580534 580215   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-curve448_tables.o /tmp/ccsuM5UA.s ...\n19.254  touch            580526 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp\n19.256  mv               580541 580533   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_ossl.d.tmp crypto/dsa/libcrypto-lib-dsa_ossl.d\n19.256  sed              580542 580160   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.260  cat              580543 580160   0 \n19.262  cat              580546 580160   0 /usr/bin/cat /proc/4193716/stat\n19.266  sh               580539 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.268  sh               580548 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.268  sh               580551 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n19.273  sh               580550 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.273  cmp              580549 580539   0 /usr/bin/cmp crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d\n19.280  touch            580552 564020   0 /usr/bin/touch crypto/hashtable/libcrypto-lib-hashfunc.d.tmp\n19.284  riscv64-linux-g  580553 580550   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.285  riscv64-linux-g  580554 580548   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.289  cmp              580556 580551   0 /usr/bin/cmp crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d\n19.291  mv               580559 580551   0 /usr/bin/mv crypto/evp/libcrypto-lib-dsa_ctrl.d.tmp crypto/evp/libcrypto-lib-dsa_ctrl.d\n19.294  mv               580555 580539   0 /usr/bin/mv crypto/evp/libcrypto-lib-p_verify.d.tmp crypto/evp/libcrypto-lib-p_verify.d\n19.294  containerd-shim  580544 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1051b837fec7188901764199513ccaf096950ed74bff371ed7e081beb8f96a4b -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1051b837fec7188901764199513ccaf096950ed74bff371ed7e081beb8f delete\n19.294  mv               580527 580486   0 /usr/bin/mv crypto/evp/libcrypto-lib-cmeth_lib.d.tmp crypto/evp/libcrypto-lib-cmeth_lib.d\n19.297  runc             580565 580544   0 \n19.297  touch            580558 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp\n19.299  touch            580566 567660   0 /usr/bin/touch crypto/dso/libcrypto-lib-dso_lib.d.tmp\n19.299  sh               580557 564020   0 /bin/sh -c if cmp crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d > /dev/null 2> /dev/null; then \\\\n\n19.304  sh               580575 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d > /dev/null 2> \n19.304  sh               580578 567660   0 /bin/sh -c if cmp crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.304  cc1              580576 580554   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_asn1.d -MF crypto/ec/libcrypto-lib-ec_asn1.d.tmp -MQ crypto/ec/libcrypto-lib-ec_asn1.o ...\n19.306  cmp              580580 580578   0 /usr/bin/cmp crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d\n19.308  cmp              580572 580557   0 /usr/bin/cmp crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d\n19.309  mv               580582 580578   0 /usr/bin/mv crypto/dso/libcrypto-lib-dso_lib.d.tmp crypto/dso/libcrypto-lib-dso_lib.d\n19.313  sh               580581 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.314  cc1              580574 580553   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_backend.d -MF crypto/ec/libcrypto-lib-ec_backend.d.tmp -MQ crypto/ec/libcrypto-lib-ec_backend.o ...\n19.316  cmp              580579 580575   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d\n19.318  rustc            580577 576007   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"game-activity\", \"native-activity\")) ...\n19.326  as               580586 580197   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.o /tmp/ccPfHTdY.s\n19.328  aarch64-linux-g  580583 580581   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.329  mv               580584 580557   0 /usr/bin/mv crypto/hashtable/libcrypto-lib-hashfunc.d.tmp crypto/hashtable/libcrypto-lib-hashfunc.d\n19.341  cc1              580588 580583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hashtable/libcrypto-lib-hashtable.d -MF crypto/hashtable/libcrypto-lib-hashtable.d.tmp -MQ crypto/hashtable/libcrypto-lib-hashtable.o -D_REENTRANT -D ...\n19.343  as               580589 580111   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.o /tmp/ccn5Rovu.s\n19.348  sh               580587 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.358  powerpc64le-lin  580596 580587   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.362  sh               580598 580342   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth7348059\n19.363  cc1              580599 580596   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_null.d -MF crypto/evp/libcrypto-lib-e_null.d.tmp -MQ crypto/evp/libcrypto-lib-e_null.o -D_REENTRANT -D ...\n19.364  sed              580602 580598   0 /usr/bin/sed -n s/^driver: //p\n19.365  as               580600 580283   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-skeymgmt_meth.o /tmp/ccuHVopt.s\n19.368  ethtool          580601 580598   0 /usr/sbin/ethtool -i veth7348059\n19.372  sh               580595 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.373  touch            580603 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp\n19.378  aarch64-linux-g  580606 580595   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.379  mv               580585 580575   0 /usr/bin/mv crypto/ec/curve448/libcrypto-lib-curve448_tables.d.tmp crypto/ec/curve448/libcrypto-lib-curve448_tables.d\n19.379  touch            580607 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp\n19.380  sh               580593 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.380  sh               580608 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d > /dev/null 2> /dev/nul\n19.382  systemd-sysctl   580609 580342   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7348059 --prefix=/net/ipv4/neigh/veth7348059 --prefix=/net/ipv6/conf/veth7348059 --prefix=/net/ipv6/neigh/veth7348059\n19.382  sh               580610 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d > /dev/null 2> /dev\n19.385  cmp              580613 580610   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d\n19.390  riscv64-linux-g  580612 580593   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.391  cc1              580616 580606   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hmac/libcrypto-lib-hmac.d -MF crypto/hmac/libcrypto-lib-hmac.d.tmp -MQ crypto/hmac/libcrypto-lib-hmac.o -D_REENTRANT -D ...\n19.394  cmp              580540 580535   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d\n19.394  cmp              580611 580608   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d\n19.397  sh               580619 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.408  mv               580618 580610   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha256.d\n19.408  powerpc64le-lin  580622 580619   0 \n19.410  cc1              580625 580622   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_old.d -MF crypto/evp/libcrypto-lib-e_old.d.tmp -MQ crypto/evp/libcrypto-lib-e_old.o -D_REENTRANT -D ...\n19.414  mv               580621 580608   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d.tmp crypto/evp/libcrypto-lib-e_aes_cbc_hmac_sha1.d\n19.414  cc1              580617 580612   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_check.d -MF crypto/ec/libcrypto-lib-ec_check.d.tmp -MQ crypto/ec/libcrypto-lib-ec_check.o ...\n19.417  as               580624 580524   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_idea.o /tmp/cc0HyC7G.s\n19.422  touch            580626 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp\n19.434  sh               580627 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d > /dev/null 2> /dev/null; then \\\\n\tr\n19.440  as               580629 580261   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-f_generic.o /tmp/ccqHqa8P.s ...\n19.443  cmp              580628 580627   0 /usr/bin/cmp crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d\n19.457  sh               580637 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.464  powerpc64le-lin  580638 580637   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.469  mv               580639 580627   0 /usr/bin/mv crypto/evp/libcrypto-lib-skeymgmt_meth.d.tmp crypto/evp/libcrypto-lib-skeymgmt_meth.d\n19.478  cc1              580641 580638   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc2.d -MF crypto/evp/libcrypto-lib-e_rc2.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc2.o -D_REENTRANT -D ...\n19.479  sh               580642 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.489  sh               580620 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.489  cc               580644 580577   0 /tmp/native-trace-574409-1783994812229/shims/cc -m64 /target/debug/build/android-activity-cf828d8ea559b7fe/rustcJ9byMS/symbols.o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.137yricpsumo729ibuhzl8j30.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.4izw380gqeii70j45vths6l1n.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8gl0knciminbylk71sqi0vobx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8uysvnewy5ac2mdanfvsi1ztx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.akwjjg0cjn8p2u7393d809f07.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.21xajqu33kzjkykxk9l4ij2ek.19pcfm5.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-56811999bf1868bb.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libjobserver-d7000c5cfc455764.rlib /target/debug/deps/liblibc-32a9bea892533c7a.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n19.492  aarch64-linux-g  580643 580642   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.492  cc               580646 580644   0 /usr/bin/cc -m64 /target/debug/build/android-activity-cf828d8ea559b7fe/rustcJ9byMS/symbols.o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.137yricpsumo729ibuhzl8j30.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.4izw380gqeii70j45vths6l1n.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8gl0knciminbylk71sqi0vobx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.8uysvnewy5ac2mdanfvsi1ztx.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.akwjjg0cjn8p2u7393d809f07.19pcfm5.rcgu /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe.21xajqu33kzjkykxk9l4ij2ek.19pcfm5.rcgu -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-56811999bf1868bb.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libjobserver-d7000c5cfc455764.rlib /target/debug/deps/liblibc-32a9bea892533c7a.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n19.495  collect2         580647 580646   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.501  ld.lld           580650 580647   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/android-activity-cf828d8ea559b7fe/build_script_build-cf828d8ea559b7fe ...\n19.501  cc1              580649 580643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hpke/libcrypto-lib-hpke.d -MF crypto/hpke/libcrypto-lib-hpke.d.tmp -MQ crypto/hpke/libcrypto-lib-hpke.o -D_REENTRANT -D ...\n19.501  touch            580648 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp\n19.506  sh               580652 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d > /dev/null 2> /dev/null; t\n19.508  cmp              580653 580652   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d\n19.508  sh               580640 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.510  riscv64-linux-g  580651 580620   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.514  mv               580655 580652   0 /usr/bin/mv crypto/ec/curve448/libcrypto-lib-f_generic.d.tmp crypto/ec/curve448/libcrypto-lib-f_generic.d\n19.520  rust-lld         580650 580647   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cccN5hdV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.520  powerpc64le-lin  580654 580640   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.526  sh               580657 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.529  cc1              580656 580651   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_curve.d -MF crypto/ec/libcrypto-lib-ec_curve.d.tmp -MQ crypto/ec/libcrypto-lib-ec_curve.o ...\n19.533  cc1              580658 580654   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc4.d -MF crypto/evp/libcrypto-lib-e_rc4.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc4.o -D_REENTRANT -D ...\n19.533  mv               580645 580535   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_lib.d.tmp crypto/dsa/libcrypto-lib-dsa_lib.d\n19.536  riscv64-linux-g  580660 580657   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.537  touch            580659 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_idea.d.tmp\n19.538  sh               580661 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.543  riscv64-linux-g  580662 580661   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.545  cc1              580663 580660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_cvt.d -MF crypto/ec/libcrypto-lib-ec_cvt.d.tmp -MQ crypto/ec/libcrypto-lib-ec_cvt.o ...\n19.546  cc1              580664 580662   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_deprecated.d -MF crypto/ec/libcrypto-lib-ec_deprecated.d.tmp -MQ crypto/ec/libcrypto-lib-ec_deprecated.o ...\n19.553  as               580665 580280   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_cast.o /tmp/cc06IJbh.s\n19.562  as               580667 580255   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-signature.o /tmp/cccoJEBl.s\n19.565  sh               580666 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.570  as               580669 580288   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_backend.o /tmp/ccWFwJ7S.s\n19.591  as               580670 579538   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dsa/libcrypto-lib-dsa_ameth.o /tmp/cca0ay8F.s ...\n19.602  touch            580671 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_cast.d.tmp\n19.607  cmp              580668 580666   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d\n19.622  touch            580690 567660   0 /usr/bin/touch crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp\n19.627  sh               580689 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.631  cmp              580691 580689   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d\n19.638  sh               580692 567660   0 /bin/sh -c if cmp crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.640  mv               580693 580666   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_idea.d.tmp crypto/evp/libcrypto-lib-e_idea.d\n19.648  cmp              580694 580692   0 /usr/bin/cmp crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d\n19.648  mv               580695 580689   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_cast.d.tmp crypto/evp/libcrypto-lib-e_cast.d\n19.650  as               580696 580350   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_dh.o /tmp/cc3Fg3Ox.s\n19.657  mv               580697 580692   0 /usr/bin/mv crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp crypto/dsa/libcrypto-lib-dsa_ameth.d\n19.658  sh               580698 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.663  sh               580699 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.665  powerpc64le-lin  580700 580698   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.669  riscv64-linux-g  580702 580699   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.670  cc1              580701 580700   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc4_hmac_md5.d -MF crypto/evp/libcrypto-lib-e_rc4_hmac_md5.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc4_hmac_md5.o -D_REENTRANT -D ...\n19.682  sh               580703 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.685  powerpc64le-lin  580705 580703   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.688  cc1              580704 580702   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_err.d -MF crypto/ec/libcrypto-lib-ec_err.d.tmp -MQ crypto/ec/libcrypto-lib-ec_err.o ...\n19.693  cc1              580707 580705   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_rc5.d -MF crypto/evp/libcrypto-lib-e_rc5.d.tmp -MQ crypto/evp/libcrypto-lib-e_rc5.o -D_REENTRANT -D ...\n19.711  touch            580688 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_backend.d.tmp\n19.712  as               580706 580612   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_check.o /tmp/ccKkJa2f.s ...\n19.714  build-script-bu  580709 576007   0 /target/debug/build/android-activity-cf828d8ea559b7fe/build-script-build\n19.723  sh               580710 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n19.723  as               580711 580157   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.o /tmp/ccQmGwp4.s ...\n19.743  touch            580713 567660   0 /usr/bin/touch crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp\n19.746  cmp              580712 580710   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d\n19.750  sh               580715 567660   0 /bin/sh -c if cmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d > /dev/null 2\n19.750  as               580714 580660   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_cvt.o /tmp/ccpA3CXe.s ...\n19.756  cmp              580716 580715   0 /usr/bin/cmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d\n19.757  mv               580717 580710   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_backend.d.tmp crypto/ffc/libcrypto-lib-ffc_backend.d\n19.762  touch            580719 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-signature.d.tmp\n19.764  sh               580720 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.766  as               580721 580662   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/libcrypto-lib-ec_deprecated.o /tmp/cch5XHMR.s ...\n19.768  as               580718 580388   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_key_validate.o /tmp/ccdr1Bfp.s\n19.769  aarch64-linux-g  580722 580720   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.771  as               580725 580596   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_null.o /tmp/ccF6KjY8.s\n19.774  sh               580723 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-signature.d.tmp crypto/evp/libcrypto-lib-signature.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.775  cc1              580726 580722   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/hpke/libcrypto-lib-hpke_util.d -MF crypto/hpke/libcrypto-lib-hpke_util.d.tmp -MQ crypto/hpke/libcrypto-lib-hpke_util.o -D_REENTRANT -D ...\n19.775  mv               580727 580715   0 /usr/bin/mv crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d.tmp crypto/ec/curve448/arch_64/libcrypto-lib-f_impl64.d\n19.790  cmp              580729 580723   0 \n19.790  mv               580734 580723   0 /usr/bin/mv crypto/evp/libcrypto-lib-signature.d.tmp crypto/evp/libcrypto-lib-signature.d\n19.790  touch            580724 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_check.d.tmp\n19.790  cmp              580732 580730   0 \n19.790  touch            580728 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_deprecated.d.tmp\n19.790  sh               580730 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_check.d.tmp crypto/ec/libcrypto-lib-ec_check.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.790  sh               580731 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d > /dev/null 2> /dev/null; then \\\\n\trm \n19.790  cmp              580733 580731   0 /usr/bin/cmp crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d\n19.790  mv               580735 580731   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_deprecated.d.tmp crypto/ec/libcrypto-lib-ec_deprecated.d\n19.792  sh               580736 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.795  riscv64-linux-g  580739 580736   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.795  mv               580737 580730   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_check.d.tmp crypto/ec/libcrypto-lib-ec_check.d\n19.799  sh               580738 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.802  cc1              580740 580739   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_key.d -MF crypto/ec/libcrypto-lib-ec_key.d.tmp -MQ crypto/ec/libcrypto-lib-ec_key.o ...\n19.812  touch            580742 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_dh.d.tmp\n19.813  touch            580741 567660   0 /usr/bin/touch crypto/ec/libcrypto-lib-ec_cvt.d.tmp\n19.816  sh               580745 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.818  riscv64-linux-g  580746 580745   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.820  riscv64-linux-g  580743 580738   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.821  cc1              580747 580746   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_lib.d -MF crypto/ec/libcrypto-lib-ec_lib.d.tmp -MQ crypto/ec/libcrypto-lib-ec_lib.o ...\n19.824  sh               580748 567660   0 /bin/sh -c if cmp crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ec/l\n19.830  cc1              580749 580743   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_kmeth.d -MF crypto/ec/libcrypto-lib-ec_kmeth.d.tmp -MQ crypto/ec/libcrypto-lib-ec_kmeth.o ...\n19.832  cmp              580750 580748   0 /usr/bin/cmp crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d\n19.838  sh               580744 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.840  touch            580751 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_null.d.tmp\n19.843  sh               580752 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ff\n19.843  aarch64-linux-g  580754 580744   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.854  cmp              580756 580752   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d\n19.857  cc1              580757 580754   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_client.d -MF crypto/http/libcrypto-lib-http_client.d.tmp -MQ crypto/http/libcrypto-lib-http_client.o -D_REENTRANT -D ...\n19.861  as               580758 580397   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/ffc/libcrypto-lib-ffc_key_generate.o /tmp/cc9ALil6.s\n19.875  mv               580755 580748   0 /usr/bin/mv crypto/ec/libcrypto-lib-ec_cvt.d.tmp crypto/ec/libcrypto-lib-ec_cvt.d\n19.875  git              580759 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n19.876  mv               580760 580752   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_dh.d.tmp crypto/ffc/libcrypto-lib-ffc_dh.d\n19.897  touch            580764 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp\n19.898  sh               580765 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d > /dev/null 2> /dev/null; the\n19.899  sh               580766 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.901  as               580763 579714   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-bio_b64.o /tmp/ccTYeAHq.s\n19.904  cmp              580767 580765   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d\n19.907  sh               580770 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.911  mv               580769 580765   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_key_generate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_generate.d\n19.911  aarch64-linux-g  580771 580770   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.915  cc1              580774 580771   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_err.d -MF crypto/http/libcrypto-lib-http_err.d.tmp -MQ crypto/http/libcrypto-lib-http_err.o -D_REENTRANT -D ...\n19.923  riscv64-linux-g  580768 580766   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.941  sh               580753 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/ev\n19.943  cmp              580776 580753   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d\n19.945  touch            580777 564020   0 /usr/bin/touch crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp\n19.946  sh               580778 564020   0 /bin/sh -c if cmp crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d > /dev/null 2> /dev/null; the\n19.948  mv               580780 580753   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_null.d.tmp crypto/evp/libcrypto-lib-e_null.d\n19.949  cmp              580779 580778   0 /usr/bin/cmp crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d\n19.952  sh               580781 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -Icrypto -Icrypto/modes -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include \n19.957  powerpc64le-lin  580782 580781   0 /usr/bin/powerpc64le-linux-gnu-gcc -Icrypto -Icrypto/modes -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC ...\n19.959  cc1              580775 580768   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/ec/libcrypto-lib-ec_mult.d -MF crypto/ec/libcrypto-lib-ec_mult.d.tmp -MQ crypto/ec/libcrypto-lib-ec_mult.o ...\n19.962  cc1              580783 580782   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I crypto -I crypto/modes -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_sm4.d -MF crypto/evp/libcrypto-lib-e_sm4.d.tmp ...\n19.970  mv               580786 580778   0 /usr/bin/mv crypto/ffc/libcrypto-lib-ffc_key_validate.d.tmp crypto/ffc/libcrypto-lib-ffc_key_validate.d\n19.986  sh               580784 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.990  sh               580788 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.990  aarch64-linux-g  580787 580784   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.994  aarch64-linux-g  580789 580788   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n20.004  cc1              580790 580787   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/http/libcrypto-lib-http_lib.d -MF crypto/http/libcrypto-lib-http_lib.d.tmp -MQ crypto/http/libcrypto-lib-http_lib.o -D_REENTRANT -D ...\n20.007  cc1              580792 580789   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/kdf/libcrypto-lib-kdf_err.d -MF crypto/kdf/libcrypto-lib-kdf_err.d.tmp -MQ crypto/kdf/libcrypto-lib-kdf_err.o -D_REENTRANT -D ...\n20.021  as               580794 580771   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/http/libcrypto-lib-http_err.o /tmp/cc34MGPl.s\n20.052  touch            580797 564020   0 /usr/bin/touch crypto/http/libcrypto-lib-http_err.d.tmp\n20.059  sh               580798 564020   0 /bin/sh -c if cmp crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n20.060  as               580793 580638   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-e_rc2.o /tmp/cczbhKVh.s\n20.071  cmp              580799 580798   0 /usr/bin/cmp crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d\n20.075  touch            580800 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-bio_b64.d.tmp\n20.081  touch            580801 564995   0 /usr/bin/touch crypto/evp/libcrypto-lib-e_rc2.d.tmp\n20.085  mv               580804 580798   0 /usr/bin/mv crypto/http/libcrypto-lib-http_err.d.tmp crypto/http/libcrypto-lib-http_err.d\n20.085  sh               580803 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n20.085  as               580802 580321   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/ec/curve448/libcrypto-lib-scalar.o /tmp/ccH3uRkm.s ...\n20.090  cmp              580806 580803   0 /usr/bin/cmp crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d\n20.095  sh               580807 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n20.102  sh               580805 564995   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/evp/\n20.111  aarch64-linux-g  580808 580807   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n20.122  mv               580812 580803   0 /usr/bin/mv crypto/evp/libcrypto-lib-bio_b64.d.tmp crypto/evp/libcrypto-lib-bio_b64.d\n20.135  cmp              580810 580805   0 /usr/bin/cmp crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d\n20.136  cc1              580813 580808   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/lhash/libcrypto-lib-lh_stats.d -MF crypto/lhash/libcrypto-lib-lh_stats.d.tmp -MQ crypto/lhash/libcrypto-lib-lh_stats.o -D_REENTRANT -D ...\n20.142  touch            580814 567660   0 /usr/bin/touch crypto/ec/curve448/libcrypto-lib-scalar.d.tmp\n20.142  as               580815 580123   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-pmeth_check.o /tmp/ccBX8USm.s\n20.145  mv               580817 580805   0 /usr/bin/mv crypto/evp/libcrypto-lib-e_rc2.d.tmp crypto/evp/libcrypto-lib-e_rc2.d\n20.154  sh               580818 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n20.154  sh               580816 567660   0 /bin/sh -c if cmp crypto/ec/curve448/libcrypto-lib-scalar.d.tmp crypto/ec/curve448/libcrypto-lib-scalar.d > /dev/null 2> /dev/null; then \\\\n\n20.160  cmp              580819 580816   0 /usr/bin/cmp crypto/ec/curve448/libcrypto-lib-scalar.d.tmp crypto/ec/curve448/libcrypto-lib-scalar.d\n20.162  powerpc64le-lin  580820 580818   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n20.166  sh               580822 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n20.170  powerpc64le-lin  580823 580822   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n20.171  cc1              580824 580820   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-e_xcbc_d.d -MF crypto/evp/libcrypto-lib-e_xcbc_d.d.tmp -MQ crypto/evp/libcrypto-lib-e_xcbc_d.o -D_REENTRANT -D ...\n20.177  cc1              580825 580823   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-ec_ctrl.d -MF crypto/evp/libcrypto-lib-ec_ctrl.d.tmp -MQ crypto/evp/libcrypto-lib-ec_ctrl.o -D_REENTRANT -D ...\n20.231  as               580828 580244   0 \n20.251  as               580830 579931   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/evp/libcrypto-lib-dh_ctrl.o /tmp/ccTD0f2P.s\n"
    },
    {
      "argv": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 573764,
      "build_script_target_dir": "dlmalloc-e249455d30ed6cef",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
      "pid": 573764,
      "ppid": 573410,
      "root_cargo_pid": 573410,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 574135,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 574135,
      "ppid": 573410,
      "root_cargo_pid": 573410,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 574135,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 574152,
      "ppid": 574135,
      "root_cargo_pid": 573410,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "dlmalloc",
      "cwd": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "event_id": "bsrun:b277b3f0917962c5:8de3aa913df56e91:cbf50263c00d1646",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
      "out_dir": "/target/debug/build/dlmalloc-e249455d30ed6cef/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
      "success": true,
      "target": null,
      "version": "0.2.4",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-aarch64-0p7uloo_/src/dlmalloc-0.2.4",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:4a171888d45fa12d:6ed0f36d8fdf2af7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "out_dir": "/target/debug/build/libc-8a22300c8f78b6db/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "success": true,
      "target": null,
      "version": "0.2.186",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 574135,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 574152,
      "ppid": 574135,
      "root_cargo_pid": 573410,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 2337,
    "crate": "dlmalloc",
    "version": "0.2.4",
    "crate_id": "97450",
    "version_id": "604514",
    "downloads": 5614643,
    "cumulative_downloads": 103859995594,
    "cumulative_share_of_global": 0.38830854684201954,
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
