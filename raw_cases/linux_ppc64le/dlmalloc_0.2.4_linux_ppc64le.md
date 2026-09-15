# `dlmalloc` `0.2.4`

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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
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
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-572402-1783994809042059912.map",
  "pid": 572402,
  "ppid": 572369,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-572402-1783994809042059912.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
      "name": "dlmalloc",
      "version": "0.2.4",
      "manifest_path": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 572402,
  "ppid": 572369,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:949e35709c6453f8:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
  "pid": 572402,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:a4b626e122136180:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "45310e3c0e9f051a76737bf92a43d9e1232bd3764d62caf77b451f1c061371fb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:42cc93c27941f753:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "993aabf035533365d094a014a9d42172cf14c3ddbdaf271509d6da84e775fc07",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:d60e88eab97cb99b:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "4be57364639ffba1aa89d5e683b477d306741335dd97400c3b039439d48295b4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:b4be949947c8206b:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "8af87650a387112e6ee1bdefee9a0eaeea7dcc2fd067d40019c3a2cbfd521f0c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:6b5e28f63f53fedc:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "256c7245c751cedadadc7838c1b2ab630d68a66414cc379c3d54a8c0aa554e37",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "used:cc:a8dba13d0541940d:8993b5944e6eb4c3:8c79bd2c85704816",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
  "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
  "pid": 572402,
  "sha256": "3b90de6ca03bdb1dce7647a1029cfc8bae30bfaf1c888b94a655900fd9aa28f8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "cargo_pkg_name": "dlmalloc",
  "cargo_pkg_version": "0.2.4",
  "context_path": "/tmp/native-trace-569412-1783994803665/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-569412-1783994803665/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 572402,
  "ppid": 572369,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
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
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
      "kind": "object",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-572402-1783994809042059912.map",
  "pid": 572402,
  "ppid": 572369,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-572402-1783994809042059912.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
  "ppid": 572368,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "event_id": "used:cc:f7a275179e4f3c0d:48bdf7df11bc0c09:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "pid": 572470,
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
  "context_path": "/tmp/native-trace-569412-1783994803665/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-569412-1783994803665/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 572470,
  "ppid": 572368,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-572470-1783994809225661750.map",
  "pid": 572470,
  "ppid": 572368,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-572470-1783994809225661750.map"
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
  "parsed_event_count": 4049,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 4050,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "         579448 579216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_cipher.o /tmp/ccvtDdxO.s\n18.175  sh               579449 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.176  touch            579450 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_dh.d.tmp\n18.182  as               579451 579051   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_rdrand.o /tmp/ccn67Bdk.s\n18.189  aarch64-linux-g  579452 579449   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.194  cc1              579455 579452   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-legacy_sha.d -MF crypto/evp/libcrypto-lib-legacy_sha.d.tmp -MQ crypto/evp/libcrypto-lib-legacy_sha.o -D_REENTRANT -D ...\n18.196  sh               579453 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.198  touch            579456 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_lib.d.tmp\n18.204  touch            579458 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_rdrand.d.tmp\n18.207  touch            579454 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-evp_fetch.d.tmp\n18.215  cmp              579457 579453   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d\n18.215  sh               579459 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.219  sh               579461 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n18.221  sh               579460 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n18.223  cmp              579462 579459   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d\n18.242  cmp              579464 579460   0 /usr/bin/cmp crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d\n18.244  cmp              579463 579461   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d\n18.244  mv               579465 579459   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d\n18.247  mv               579467 579453   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d\n18.252  mv               579468 579461   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d\n18.254  sh               579469 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.261  powerpc64le-lin  579470 579469   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.261  mv               579466 579460   0 /usr/bin/mv crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d\n18.269  touch            579471 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_cipher.d.tmp\n18.275  touch            579473 567660   0 /usr/bin/touch crypto/crmf/libcrypto-lib-crmf_lib.d.tmp\n18.276  sh               579472 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.280  powerpc64le-lin  579475 579472   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.282  sh               579474 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d > /dev/null 2> /dev/null; then \\\\n\trm \n18.285  sh               579478 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.288  sh               579477 567660   0 /bin/sh -c if cmp crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n18.288  sh               579480 564020   0 \n18.288  cmp              579479 579474   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d\n18.289  aarch64-linux-g  579481 579480   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.292  cc1              579476 579470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_blocks.d -MF crypto/err/libcrypto-lib-err_blocks.d.tmp -MQ crypto/err/libcrypto-lib-err_blocks.o -D_REENTRANT -D ...\n18.294  cmp              579483 579477   0 /usr/bin/cmp crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d\n18.295  mv               579484 579474   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d\n18.296  powerpc64le-lin  579485 579478   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.301  cc1              579482 579475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_mark.d -MF crypto/err/libcrypto-lib-err_mark.d.tmp -MQ crypto/err/libcrypto-lib-err_mark.o -D_REENTRANT -D ...\n18.307  cc1              579486 579481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-legacy_wp.d -MF crypto/evp/libcrypto-lib-legacy_wp.d.tmp -MQ crypto/evp/libcrypto-lib-legacy_wp.o -D_REENTRANT -D ...\n18.312  mv               579487 579477   0 /usr/bin/mv crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d\n18.320  sh               579489 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.320  cc1              579488 579485   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_prn.d -MF crypto/err/libcrypto-lib-err_prn.d.tmp -MQ crypto/err/libcrypto-lib-err_prn.o -D_REENTRANT -D ...\n18.324  sh               579493 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.327  as               579494 579358   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_depr.o /tmp/ccC6D7iF.s ...\n18.331  powerpc64le-lin  579492 579489   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.334  riscv64-linux-g  579495 579493   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.340  cc1              579497 579492   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_save.d -MF crypto/err/libcrypto-lib-err_save.d.tmp -MQ crypto/err/libcrypto-lib-err_save.o -D_REENTRANT -D ...\n18.342  cc1              579496 579495   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dh/libcrypto-lib-dh_prn.d -MF crypto/dh/libcrypto-lib-dh_prn.d.tmp -MQ crypto/dh/libcrypto-lib-dh_prn.o ...\n18.361  as               579499 579342   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_blake2.o /tmp/ccwHGlli.s\n18.367  touch            579498 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_depr.d.tmp\n18.375  as               579500 579423   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_mdc2.o /tmp/ccHMPTjs.s\n18.383  sh               579501 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n18.389  cmp              579502 579501   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d\n18.406  mv               579503 579501   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d\n18.420  sh               579504 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.428  as               579505 579348   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_check.o /tmp/cce1THk8.s ...\n18.429  riscv64-linux-g  579506 579504   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.437  cc1              579507 579506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dh/libcrypto-lib-dh_rfc5114.d -MF crypto/dh/libcrypto-lib-dh_rfc5114.d.tmp -MQ crypto/dh/libcrypto-lib-dh_rfc5114.o ...\n18.456  as               579508 579437   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_ripemd.o /tmp/ccKumy2t.s\n18.475  touch            579509 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_blake2.d.tmp\n18.482  touch            579514 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp\n18.491  touch            579515 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp\n18.492  rustc            579513 576080   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-3.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f79375e4284bff60 ...\n18.496  sh               579516 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.501  sh               579518 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n18.506  sh               579521 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.508  touch            579519 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_check.d.tmp\n18.508  cmp              579523 579521   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d\n18.512  cmp              579522 579518   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d\n18.513  cmp              579517 579516   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d\n18.518  as               579524 578972   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-kdf_meth.o /tmp/cciddI4j.s\n18.528  sh               579526 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n18.530  cmp              579528 579526   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d\n18.535  mv               579529 579516   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d\n18.538  mv               579527 579521   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d\n18.540  mv               579530 579526   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d\n18.550  sh               579536 567660   0 \n18.550  mv               579535 579518   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d\n18.558  riscv64-linux-g  579538 579536   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.558  sh               579539 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.569  aarch64-linux-g  579541 579539   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.582  sh               579542 564020   0 \n18.582  aarch64-linux-g  579545 579542   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.587  cc1              579550 579541   0 \n18.588  cc1              579543 579538   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_ameth.d -MF crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_ameth.o ...\n18.592  cc1              579551 579545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-m_sigver.d -MF crypto/evp/libcrypto-lib-m_sigver.d.tmp -MQ crypto/evp/libcrypto-lib-m_sigver.o -D_REENTRANT -D ...\n18.599  as               579552 579352   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_err.o /tmp/ccutk9F1.s ...\n18.606  rustc            579549 576007   0 \n18.607  sh               579554 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.618  aarch64-linux-g  579558 579554   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.618  touch            579557 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp\n18.623  as               579560 579434   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_all.o /tmp/ccatqYpi.s\n18.646  as               579572 579379   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_kdf.o /tmp/ccGmSPy2.s ...\n18.662  touch            579569 567660   0 \n18.662  as               579555 579446   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_all_legacy.o /tmp/ccKd0YDa.s\n18.667  touch            579574 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_all.d.tmp\n18.671  sh               579578 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n18.671  cc1              579559 579558   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-mac_lib.d -MF crypto/evp/libcrypto-lib-mac_lib.d.tmp -MQ crypto/evp/libcrypto-lib-mac_lib.o -D_REENTRANT -D ...\n18.676  touch            579577 567660   0 \n18.686  cmp              579580 579578   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d\n18.696  as               579583 578992   0 \n18.700  sh               579566 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d > /dev/null 2> /dev\n18.704  as               579570 578990   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_list.o /tmp/ccZDmvBH.s\n18.711  sh               579582 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n18.711  mv               579586 579578   0 /usr/bin/mv crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d\n18.719  cmp              579588 579566   0 /usr/bin/cmp crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d\n18.719  cmp              579590 579582   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d\n18.727  sh               579592 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n18.734  mv               579591 579566   0 /usr/bin/mv crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d\n18.738  cmp              579593 579592   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d\n18.744  mv               579594 579582   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d\n18.756  touch            579598 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_all_legacy.d.tmp\n18.759  mv               579599 579592   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d\n18.761  sh               579600 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.774  touch            579604 567660   0 /usr/bin/touch crypto/des/libcrypto-lib-fcrypt_b.d.tmp\n18.777  powerpc64le-lin  579602 579600   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.786  cc1              579607 579602   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_asn1.d -MF crypto/ess/libcrypto-lib-ess_asn1.d.tmp -MQ crypto/ess/libcrypto-lib-ess_asn1.o -D_REENTRANT -D ...\n18.788  sh               579603 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d > /dev/null 2> /dev/null; then \\\\n\n18.791  cmp              579608 579603   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d\n18.794  sh               579605 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.800  as               579610 579228   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-keymgmt_lib.o /tmp/ccJLRBbG.s\n18.800  touch            579587 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-kdf_meth.d.tmp\n18.802  sh               579611 567660   0 /bin/sh -c if cmp crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.810  mv               579613 579603   0 /usr/bin/mv crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d\n18.812  sh               579612 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.816  sh               579617 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.819  sh               579616 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.832  cmp              579620 579616   0 /usr/bin/cmp crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d\n18.835  cmp              579615 579611   0 /usr/bin/cmp crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d\n18.837  riscv64-linux-g  579622 579617   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.838  sh               579623 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.839  cc1              579625 579622   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_backend.d -MF crypto/dsa/libcrypto-lib-dsa_backend.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_backend.o ...\n18.844  mv               579624 579611   0 /usr/bin/mv crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d\n18.845  powerpc64le-lin  579626 579623   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.847  riscv64-linux-g  579621 579605   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.851  touch            579627 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_list.d.tmp\n18.856  cc1              579629 579621   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_asn1.d -MF crypto/dsa/libcrypto-lib-dsa_asn1.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_asn1.o ...\n18.856  mv               579628 579616   0 /usr/bin/mv crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d\n18.857  aarch64-linux-g  579618 579612   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.873  sh               579635 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.875  sh               579630 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n18.878  cc1              579632 579618   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-mac_meth.d -MF crypto/evp/libcrypto-lib-mac_meth.d.tmp -MQ crypto/evp/libcrypto-lib-mac_meth.o -D_REENTRANT -D ...\n18.881  cmp              579637 579630   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d\n18.882  cc1              579633 579626   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_err.d -MF crypto/ess/libcrypto-lib-ess_err.d.tmp -MQ crypto/ess/libcrypto-lib-ess_err.o -D_REENTRANT -D ...\n18.886  aarch64-linux-g  579636 579635   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.886  as               579640 579226   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_digest.o /tmp/cct6Kvaz.s\n18.888  sh               579639 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.892  mv               579642 579630   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d\n18.893  riscv64-linux-g  579641 579639   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.896  as               579638 579344   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_md4.o /tmp/ccAPQr8t.s\n18.908  cc1              579644 579636   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-names.d -MF crypto/evp/libcrypto-lib-names.d.tmp -MQ crypto/evp/libcrypto-lib-names.o -D_REENTRANT -D ...\n18.911  cc1              579646 579641   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_check.d -MF crypto/dsa/libcrypto-lib-dsa_check.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_check.o ...\n18.914  sh               579645 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.931  powerpc64le-lin  579647 579645   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.958  touch            579651 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_digest.d.tmp\n18.960  cc1              579652 579647   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_lib.d -MF crypto/ess/libcrypto-lib-ess_lib.d.tmp -MQ crypto/ess/libcrypto-lib-ess_lib.o -D_REENTRANT -D ...\n18.966  sh               579653 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d > /dev/null 2> /dev/null; then \\\\n\trm \n18.968  cmp              579654 579653   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d\n18.983  mv               579658 579653   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d\n18.991  as               579650 579155   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_table.o /tmp/ccJbx9tc.s\n18.999  touch            579659 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_md4.d.tmp\n19.009  sh               579661 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.012  cmp              579663 579661   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d\n19.012  sh               579662 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.018  as               579665 579382   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_group_params.o /tmp/ccETYzmu.s ...\n19.025  mv               579666 579661   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d\n19.030  sh               579667 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.033  powerpc64le-lin  579664 579662   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.043  as               579669 579119   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-kem.o /tmp/cckwspjs.s\n19.047  aarch64-linux-g  579668 579667   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.051  as               579671 579331   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_asn1.o /tmp/ccpFtpNi.s ...\n19.060  touch            579674 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_group_params.d.tmp\n19.060  as               579673 579406   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_md5_sha1.o /tmp/cciSmI68.s\n19.067  cc1              579675 579668   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p5_crpt.d -MF crypto/evp/libcrypto-lib-p5_crpt.d.tmp -MQ crypto/evp/libcrypto-lib-p5_crpt.o -D_REENTRANT -D ...\n19.073  touch            579676 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp\n19.080  sh               579677 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d > /dev/null 2> /dev/null; then \\\\n\n19.084  touch            579678 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_asn1.d.tmp\n19.086  cmp              579679 579677   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d\n19.092  sh               579682 564020   0 \n19.095  mv               579681 579677   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d\n19.096  sh               579680 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n19.100  cmp              579684 579680   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d\n19.108  sh               579688 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.113  riscv64-linux-g  579689 579688   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.114  mv               579687 579680   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d\n19.120  cc1              579690 579689   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_depr.d -MF crypto/dsa/libcrypto-lib-dsa_depr.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_depr.o ...\n19.122  touch            579691 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_table.d.tmp\n19.131  sh               579692 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d > /dev/null 2> /dev/null; then \\\\n\trm \n19.133  cmp              579683 579682   0 /usr/bin/cmp crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp crypto/evp/libcrypto-lib-keymgmt_lib.d\n19.135  touch            579693 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp\n19.137  cmp              579695 579692   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d\n19.141  cc1              579672 579664   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-asymcipher.d -MF crypto/evp/libcrypto-lib-asymcipher.d.tmp -MQ crypto/evp/libcrypto-lib-asymcipher.o -D_REENTRANT -D ...\n19.145  sh               579694 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.153  mv               579696 579692   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d\n19.153  riscv64-linux-g  579698 579694   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.157  sh               579697 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d > /dev/null 2> /dev/null; then \n19.165  mv               579699 579682   0 /usr/bin/mv crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp crypto/evp/libcrypto-lib-keymgmt_lib.d\n19.169  cmp              579701 579697   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d\n19.170  cc1              579702 579698   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_err.d -MF crypto/dsa/libcrypto-lib-dsa_err.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_err.o ...\n19.191  mv               579706 579697   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d\n19.192  sh               579707 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.195  as               579705 579347   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_backend.o /tmp/cc7wiMqw.s ...\n19.196  as               579708 579470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_blocks.o /tmp/ccH7bth2.s\n19.198  sh               579704 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.200  aarch64-linux-g  579709 579707   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.201  as               579710 579371   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_gen.o /tmp/ccRIA1d6.s ...\n19.210  as               579712 579418   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_meth.o /tmp/ccmfJaXa.s ...\n19.212  as               579711 579481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_wp.o /tmp/ccKB62gP.s\n19.218  powerpc64le-lin  579714 579704   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.220  as               579713 579320   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_eckey.o /tmp/ccPHrDRF.s\n19.228  touch            579715 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_blocks.d.tmp\n19.232  touch            579718 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_backend.d.tmp\n19.235  as               579717 579265   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_dsa.o /tmp/ccIMIjDw.s\n19.235  cc1              579719 579709   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p5_crpt2.d -MF crypto/evp/libcrypto-lib-p5_crpt2.d.tmp -MQ crypto/evp/libcrypto-lib-p5_crpt2.o -D_REENTRANT -D ...\n19.239  sh               579721 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.239  cc1              579720 579714   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_b64.d -MF crypto/evp/libcrypto-lib-bio_b64.d.tmp -MQ crypto/evp/libcrypto-lib-bio_b64.o -D_REENTRANT -D ...\n19.254  sh               579723 567660   0 \n19.256  cmp              579722 579721   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d\n19.256  touch            579724 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_gen.d.tmp\n19.260  as               579726 579626   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/ess/libcrypto-lib-ess_err.o /tmp/ccq7rI7L.s\n19.260  touch            579728 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_meth.d.tmp\n19.262  sh               579727 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.273  aarch64-linux-g  579730 579727   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.283  mv               579732 579721   0 /usr/bin/mv crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d\n19.289  cc1              579731 579730   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_dec.d -MF crypto/evp/libcrypto-lib-p_dec.d.tmp -MQ crypto/evp/libcrypto-lib-p_dec.o -D_REENTRANT -D ...\n19.292  touch            579733 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_dsa.d.tmp\n19.292  touch            579734 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-kem.d.tmp\n19.300  touch            579735 564995   0 /usr/bin/touch crypto/ess/libcrypto-lib-ess_err.d.tmp\n19.305  sh               579736 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.306  sh               579729 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n19.312  sh               579737 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n19.315  sh               579738 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.317  cmp              579740 579729   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d\n19.318  cmp              579725 579723   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_backend.d.tmp crypto/dh/libcrypto-lib-dh_backend.d\n19.322  touch            579742 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_eckey.d.tmp\n19.322  cmp              579741 579737   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d\n19.325  as               579743 578934   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-exchange.o /tmp/cc8y5pFr.s\n19.325  cmp              579739 579736   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d\n19.328  sh               579744 564995   0 /bin/sh -c if cmp crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.329  powerpc64le-lin  579745 579738   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.336  cmp              579749 579744   0 /usr/bin/cmp crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d\n19.337  mv               579747 579729   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d\n19.339  mv               579746 579723   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_backend.d.tmp crypto/dh/libcrypto-lib-dh_backend.d\n19.342  sh               579750 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n19.346  mv               579753 579737   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d\n19.347  mv               579755 579744   0 /usr/bin/mv crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d\n19.350  cc1              579757 579745   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_enc.d -MF crypto/evp/libcrypto-lib-bio_enc.d.tmp -MQ crypto/evp/libcrypto-lib-bio_enc.o -D_REENTRANT -D ...\n19.352  mv               579754 579736   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d\n19.355  cmp              579758 579750   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d\n19.356  sh               579761 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.358  sh               579748 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/evp/libc\n19.360  cmp              579762 579748   0 /usr/bin/cmp crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d\n19.360  as               579760 579452   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_sha.o /tmp/ccD4odSB.s\n19.361  as               579756 579381   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_rand.o /tmp/ccHs3Z5e.s\n19.365  riscv64-linux-g  579763 579761   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.368  mv               579764 579750   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d\n19.376  cc1              579767 579763   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_gen.d -MF crypto/dsa/libcrypto-lib-dsa_gen.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_gen.o ...\n19.376  sh               579766 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.378  powerpc64le-lin  579770 579766   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.380  touch            579768 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_wp.d.tmp\n19.389  sh               579771 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.391  mv               579769 579748   0 /usr/bin/mv crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d\n19.391  sh               579774 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.395  cc1              579773 579770   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_md.d -MF crypto/evp/libcrypto-lib-bio_md.d.tmp -MQ crypto/evp/libcrypto-lib-bio_md.o -D_REENTRANT -D ...\n19.395  as               579772 579441   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_pmeth.o /tmp/ccSTec0i.s ...\n19.398  sh               579778 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.404  powerpc64le-lin  579775 579771   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.404  cmp              579779 579778   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d\n19.408  as               579781 579181   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_ameth.o /tmp/ccjmrbCz.s ...\n19.409  mv               579780 579778   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d\n19.413  sh               579777 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.416  riscv64-linux-g  579776 579774   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.418  sh               579782 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.419  powerpc64le-lin  579784 579777   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.427  aarch64-linux-g  579785 579782   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.433  cc1              579787 579784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-c_allc.d -MF crypto/evp/libcrypto-lib-c_allc.d.tmp -MQ crypto/evp/libcrypto-lib-c_allc.o -D_REENTRANT -D ...\n19.433  cc1              579786 579776   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_key.d -MF crypto/dsa/libcrypto-lib-dsa_key.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_key.o ...\n19.437  cc1              579789 579775   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_ok.d -MF crypto/evp/libcrypto-lib-bio_ok.d.tmp -MQ crypto/evp/libcrypto-lib-bio_ok.o -D_REENTRANT -D ...\n19.440  as               579792 579387   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_rsa.o /tmp/ccdQXr0I.s\n19.443  as               579790 579475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_mark.o /tmp/ccSwUwCo.s\n19.443  sh               579794 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.446  sh               579788 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.449  as               579793 579392   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_lib.o /tmp/ccWDkEhv.s ...\n19.450  cc1              579791 579785   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_enc.d -MF crypto/evp/libcrypto-lib-p_enc.d.tmp -MQ crypto/evp/libcrypto-lib-p_enc.o -D_REENTRANT -D ...\n19.451  riscv64-linux-g  579796 579794   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.453  touch            579797 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_ameth.d.tmp\n19.463  sh               579801 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.463  as               579798 578905   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-evp_rand.o /tmp/ccuww5qj.s\n19.468  as               579802 579495   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_prn.o /tmp/cchSsnk0.s ...\n19.469  cmp              579803 579801   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d\n19.477  cc1              579800 579796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_lib.d -MF crypto/dsa/libcrypto-lib-dsa_lib.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_lib.o ...\n19.478  mv               579805 579801   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d\n19.483  aarch64-linux-g  579799 579788   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.487  sh               579808 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.490  cc1              579809 579799   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_legacy.d -MF crypto/evp/libcrypto-lib-p_legacy.d.tmp -MQ crypto/evp/libcrypto-lib-p_legacy.o -D_REENTRANT -D ...\n19.497  riscv64-linux-g  579810 579808   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.503  cc1              579812 579810   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_meth.d -MF crypto/dsa/libcrypto-lib-dsa_meth.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_meth.o ...\n19.505  touch            579806 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_rand.d.tmp\n19.505  touch            579811 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_prn.d.tmp\n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 572440,
  "build_script_target_dir": "dlmalloc-e249455d30ed6cef",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
  "pid": 572440,
  "ppid": 572351,
  "root_cargo_pid": 572351,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
  "build_script_root_pid": 572513,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 572513,
  "ppid": 572351,
  "root_cargo_pid": 572351,
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
  "build_script_root_pid": 572513,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 572514,
  "ppid": 572513,
  "root_cargo_pid": 572351,
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
  "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "event_id": "bsrun:7b072982c1151f5c:8de3aa913df56e91:cbf50263c00d1646",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
  "out_dir": "/target/debug/build/dlmalloc-e249455d30ed6cef/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
  "success": true,
  "target": null,
  "version": "0.2.4",
  "_owner": {
    "crate": "dlmalloc",
    "version": "0.2.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
  "build_script_root_pid": 572513,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 572514,
  "ppid": 572513,
  "root_cargo_pid": 572351,
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
  "time": "2026-07-14T02:07:08.752157+00:00",
  "crate": "dlmalloc",
  "version": "0.2.4",
  "architecture": "ppc64le",
  "duration_seconds": 28.742636060807854,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "manifest_path": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
          "name": "dlmalloc",
          "version": "0.2.4",
          "manifest_path": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 572402,
      "ppid": 572369,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:949e35709c6453f8:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
      "pid": 572402,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:a4b626e122136180:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "45310e3c0e9f051a76737bf92a43d9e1232bd3764d62caf77b451f1c061371fb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:42cc93c27941f753:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "993aabf035533365d094a014a9d42172cf14c3ddbdaf271509d6da84e775fc07",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:d60e88eab97cb99b:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "4be57364639ffba1aa89d5e683b477d306741335dd97400c3b039439d48295b4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:b4be949947c8206b:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "8af87650a387112e6ee1bdefee9a0eaeea7dcc2fd067d40019c3a2cbfd521f0c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:6b5e28f63f53fedc:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "256c7245c751cedadadc7838c1b2ab630d68a66414cc379c3d54a8c0aa554e37",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "used:cc:a8dba13d0541940d:8993b5944e6eb4c3:8c79bd2c85704816",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef",
      "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
      "pid": 572402,
      "sha256": "3b90de6ca03bdb1dce7647a1029cfc8bae30bfaf1c888b94a655900fd9aa28f8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "cargo_pkg_name": "dlmalloc",
      "cargo_pkg_version": "0.2.4",
      "context_path": "/tmp/native-trace-569412-1783994803665/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-569412-1783994803665/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 572402,
      "ppid": 572369,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
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
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/rustcHkZR0w/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.4a4inv2jocmvo5lh2ktquwm8c.1eaftjx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5a56j4j5o03bsl226rinr1s2o.1eaftjx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.5rexvjviu5f03h68s2bbybkja.1eaftjx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.618r5mvpmtqxtz7ky8l1k9zqb.1eaftjx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.a1fsnzx4nd5fdo73w3flky5o1.1eaftjx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/dlmalloc-e249455d30ed6cef",
          "kind": "object",
          "path": "/target/debug/build/dlmalloc-e249455d30ed6cef/build_script_build-e249455d30ed6cef.f2nnuxitip77af6lnc5gqinbc.1eaftjx.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-572402-1783994809042059912.map",
      "pid": 572402,
      "ppid": 572369,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-572402-1783994809042059912.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
      "ppid": 572368,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "event_id": "used:cc:f7a275179e4f3c0d:48bdf7df11bc0c09:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "pid": 572470,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
      "context_path": "/tmp/native-trace-569412-1783994803665/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-569412-1783994803665/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 572470,
      "ppid": 572368,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcwvA202/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-572470-1783994809225661750.map",
      "pid": 572470,
      "ppid": 572368,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-572470-1783994809225661750.map"
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
      "parsed_event_count": 4049,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 4050,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "         579448 579216   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_cipher.o /tmp/ccvtDdxO.s\n18.175  sh               579449 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.176  touch            579450 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_dh.d.tmp\n18.182  as               579451 579051   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_rdrand.o /tmp/ccn67Bdk.s\n18.189  aarch64-linux-g  579452 579449   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.194  cc1              579455 579452   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-legacy_sha.d -MF crypto/evp/libcrypto-lib-legacy_sha.d.tmp -MQ crypto/evp/libcrypto-lib-legacy_sha.o -D_REENTRANT -D ...\n18.196  sh               579453 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.198  touch            579456 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_lib.d.tmp\n18.204  touch            579458 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_rdrand.d.tmp\n18.207  touch            579454 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-evp_fetch.d.tmp\n18.215  cmp              579457 579453   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d\n18.215  sh               579459 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.219  sh               579461 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n18.221  sh               579460 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n18.223  cmp              579462 579459   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d\n18.242  cmp              579464 579460   0 /usr/bin/cmp crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d\n18.244  cmp              579463 579461   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d\n18.244  mv               579465 579459   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_rdrand.d.tmp crypto/engine/libcrypto-lib-eng_rdrand.d\n18.247  mv               579467 579453   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_dh.d.tmp crypto/engine/libcrypto-lib-tb_dh.d\n18.252  mv               579468 579461   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_lib.d.tmp crypto/engine/libcrypto-lib-eng_lib.d\n18.254  sh               579469 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.261  powerpc64le-lin  579470 579469   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.261  mv               579466 579460   0 /usr/bin/mv crypto/evp/libcrypto-lib-evp_fetch.d.tmp crypto/evp/libcrypto-lib-evp_fetch.d\n18.269  touch            579471 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_cipher.d.tmp\n18.275  touch            579473 567660   0 /usr/bin/touch crypto/crmf/libcrypto-lib-crmf_lib.d.tmp\n18.276  sh               579472 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.280  powerpc64le-lin  579475 579472   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.282  sh               579474 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d > /dev/null 2> /dev/null; then \\\\n\trm \n18.285  sh               579478 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.288  sh               579477 567660   0 /bin/sh -c if cmp crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n18.288  sh               579480 564020   0 \n18.288  cmp              579479 579474   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d\n18.289  aarch64-linux-g  579481 579480   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.292  cc1              579476 579470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_blocks.d -MF crypto/err/libcrypto-lib-err_blocks.d.tmp -MQ crypto/err/libcrypto-lib-err_blocks.o -D_REENTRANT -D ...\n18.294  cmp              579483 579477   0 /usr/bin/cmp crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d\n18.295  mv               579484 579474   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_cipher.d.tmp crypto/engine/libcrypto-lib-tb_cipher.d\n18.296  powerpc64le-lin  579485 579478   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.301  cc1              579482 579475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_mark.d -MF crypto/err/libcrypto-lib-err_mark.d.tmp -MQ crypto/err/libcrypto-lib-err_mark.o -D_REENTRANT -D ...\n18.307  cc1              579486 579481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-legacy_wp.d -MF crypto/evp/libcrypto-lib-legacy_wp.d.tmp -MQ crypto/evp/libcrypto-lib-legacy_wp.o -D_REENTRANT -D ...\n18.312  mv               579487 579477   0 /usr/bin/mv crypto/crmf/libcrypto-lib-crmf_lib.d.tmp crypto/crmf/libcrypto-lib-crmf_lib.d\n18.320  sh               579489 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.320  cc1              579488 579485   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_prn.d -MF crypto/err/libcrypto-lib-err_prn.d.tmp -MQ crypto/err/libcrypto-lib-err_prn.o -D_REENTRANT -D ...\n18.324  sh               579493 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.327  as               579494 579358   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_depr.o /tmp/ccC6D7iF.s ...\n18.331  powerpc64le-lin  579492 579489   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.334  riscv64-linux-g  579495 579493   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.340  cc1              579497 579492   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/err/libcrypto-lib-err_save.d -MF crypto/err/libcrypto-lib-err_save.d.tmp -MQ crypto/err/libcrypto-lib-err_save.o -D_REENTRANT -D ...\n18.342  cc1              579496 579495   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dh/libcrypto-lib-dh_prn.d -MF crypto/dh/libcrypto-lib-dh_prn.d.tmp -MQ crypto/dh/libcrypto-lib-dh_prn.o ...\n18.361  as               579499 579342   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_blake2.o /tmp/ccwHGlli.s\n18.367  touch            579498 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_depr.d.tmp\n18.375  as               579500 579423   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_mdc2.o /tmp/ccHMPTjs.s\n18.383  sh               579501 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n18.389  cmp              579502 579501   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d\n18.406  mv               579503 579501   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_depr.d.tmp crypto/dh/libcrypto-lib-dh_depr.d\n18.420  sh               579504 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.428  as               579505 579348   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_check.o /tmp/cce1THk8.s ...\n18.429  riscv64-linux-g  579506 579504   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.437  cc1              579507 579506   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dh/libcrypto-lib-dh_rfc5114.d -MF crypto/dh/libcrypto-lib-dh_rfc5114.d.tmp -MQ crypto/dh/libcrypto-lib-dh_rfc5114.o ...\n18.456  as               579508 579437   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_ripemd.o /tmp/ccKumy2t.s\n18.475  touch            579509 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_blake2.d.tmp\n18.482  touch            579514 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp\n18.491  touch            579515 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp\n18.492  rustc            579513 576080   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_crate --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro-crate-3.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=f79375e4284bff60 ...\n18.496  sh               579516 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.501  sh               579518 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n18.506  sh               579521 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d > /dev/null 2> /dev/null; then \\\\n\tr\n18.508  touch            579519 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_check.d.tmp\n18.508  cmp              579523 579521   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d\n18.512  cmp              579522 579518   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d\n18.513  cmp              579517 579516   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d\n18.518  as               579524 578972   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-kdf_meth.o /tmp/cciddI4j.s\n18.528  sh               579526 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n18.530  cmp              579528 579526   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d\n18.535  mv               579529 579516   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_blake2.d.tmp crypto/evp/libcrypto-lib-legacy_blake2.d\n18.538  mv               579527 579521   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_ripemd.d.tmp crypto/evp/libcrypto-lib-legacy_ripemd.d\n18.540  mv               579530 579526   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_check.d.tmp crypto/dh/libcrypto-lib-dh_check.d\n18.550  sh               579536 567660   0 \n18.550  mv               579535 579518   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_mdc2.d.tmp crypto/evp/libcrypto-lib-legacy_mdc2.d\n18.558  riscv64-linux-g  579538 579536   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.558  sh               579539 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.569  aarch64-linux-g  579541 579539   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.582  sh               579542 564020   0 \n18.582  aarch64-linux-g  579545 579542   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.587  cc1              579550 579541   0 \n18.588  cc1              579543 579538   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_ameth.d -MF crypto/dsa/libcrypto-lib-dsa_ameth.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_ameth.o ...\n18.592  cc1              579551 579545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-m_sigver.d -MF crypto/evp/libcrypto-lib-m_sigver.d.tmp -MQ crypto/evp/libcrypto-lib-m_sigver.o -D_REENTRANT -D ...\n18.599  as               579552 579352   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_err.o /tmp/ccutk9F1.s ...\n18.606  rustc            579549 576007   0 \n18.607  sh               579554 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.618  aarch64-linux-g  579558 579554   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.618  touch            579557 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp\n18.623  as               579560 579434   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_all.o /tmp/ccatqYpi.s\n18.646  as               579572 579379   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_kdf.o /tmp/ccGmSPy2.s ...\n18.662  touch            579569 567660   0 \n18.662  as               579555 579446   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_all_legacy.o /tmp/ccKd0YDa.s\n18.667  touch            579574 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_all.d.tmp\n18.671  sh               579578 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n18.671  cc1              579559 579558   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-mac_lib.d -MF crypto/evp/libcrypto-lib-mac_lib.d.tmp -MQ crypto/evp/libcrypto-lib-mac_lib.o -D_REENTRANT -D ...\n18.676  touch            579577 567660   0 \n18.686  cmp              579580 579578   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d\n18.696  as               579583 578992   0 \n18.700  sh               579566 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d > /dev/null 2> /dev\n18.704  as               579570 578990   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_list.o /tmp/ccZDmvBH.s\n18.711  sh               579582 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n18.711  mv               579586 579578   0 /usr/bin/mv crypto/err/libcrypto-lib-err_all.d.tmp crypto/err/libcrypto-lib-err_all.d\n18.719  cmp              579588 579566   0 /usr/bin/cmp crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d\n18.719  cmp              579590 579582   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d\n18.727  sh               579592 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n18.734  mv               579591 579566   0 /usr/bin/mv crypto/evp/libcrypto-lib-ctrl_params_translate.d.tmp crypto/evp/libcrypto-lib-ctrl_params_translate.d\n18.738  cmp              579593 579592   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d\n18.744  mv               579594 579582   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_err.d.tmp crypto/dh/libcrypto-lib-dh_err.d\n18.756  touch            579598 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_all_legacy.d.tmp\n18.759  mv               579599 579592   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_kdf.d.tmp crypto/dh/libcrypto-lib-dh_kdf.d\n18.761  sh               579600 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.774  touch            579604 567660   0 /usr/bin/touch crypto/des/libcrypto-lib-fcrypt_b.d.tmp\n18.777  powerpc64le-lin  579602 579600   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.786  cc1              579607 579602   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_asn1.d -MF crypto/ess/libcrypto-lib-ess_asn1.d.tmp -MQ crypto/ess/libcrypto-lib-ess_asn1.o -D_REENTRANT -D ...\n18.788  sh               579603 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d > /dev/null 2> /dev/null; then \\\\n\n18.791  cmp              579608 579603   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d\n18.794  sh               579605 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.800  as               579610 579228   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-keymgmt_lib.o /tmp/ccJLRBbG.s\n18.800  touch            579587 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-kdf_meth.d.tmp\n18.802  sh               579611 567660   0 /bin/sh -c if cmp crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.810  mv               579613 579603   0 /usr/bin/mv crypto/err/libcrypto-lib-err_all_legacy.d.tmp crypto/err/libcrypto-lib-err_all_legacy.d\n18.812  sh               579612 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.816  sh               579617 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.819  sh               579616 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypt\n18.832  cmp              579620 579616   0 /usr/bin/cmp crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d\n18.835  cmp              579615 579611   0 /usr/bin/cmp crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d\n18.837  riscv64-linux-g  579622 579617   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.838  sh               579623 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.839  cc1              579625 579622   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_backend.d -MF crypto/dsa/libcrypto-lib-dsa_backend.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_backend.o ...\n18.844  mv               579624 579611   0 /usr/bin/mv crypto/des/libcrypto-lib-fcrypt_b.d.tmp crypto/des/libcrypto-lib-fcrypt_b.d\n18.845  powerpc64le-lin  579626 579623   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.847  riscv64-linux-g  579621 579605   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.851  touch            579627 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_list.d.tmp\n18.856  cc1              579629 579621   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_asn1.d -MF crypto/dsa/libcrypto-lib-dsa_asn1.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_asn1.o ...\n18.856  mv               579628 579616   0 /usr/bin/mv crypto/evp/libcrypto-lib-kdf_meth.d.tmp crypto/evp/libcrypto-lib-kdf_meth.d\n18.857  aarch64-linux-g  579618 579612   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.873  sh               579635 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n18.875  sh               579630 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n18.878  cc1              579632 579618   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-mac_meth.d -MF crypto/evp/libcrypto-lib-mac_meth.d.tmp -MQ crypto/evp/libcrypto-lib-mac_meth.o -D_REENTRANT -D ...\n18.881  cmp              579637 579630   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d\n18.882  cc1              579633 579626   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_err.d -MF crypto/ess/libcrypto-lib-ess_err.d.tmp -MQ crypto/ess/libcrypto-lib-ess_err.o -D_REENTRANT -D ...\n18.886  aarch64-linux-g  579636 579635   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n18.886  as               579640 579226   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_digest.o /tmp/cct6Kvaz.s\n18.888  sh               579639 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n18.892  mv               579642 579630   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_list.d.tmp crypto/engine/libcrypto-lib-eng_list.d\n18.893  riscv64-linux-g  579641 579639   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n18.896  as               579638 579344   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_md4.o /tmp/ccAPQr8t.s\n18.908  cc1              579644 579636   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-names.d -MF crypto/evp/libcrypto-lib-names.d.tmp -MQ crypto/evp/libcrypto-lib-names.o -D_REENTRANT -D ...\n18.911  cc1              579646 579641   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_check.d -MF crypto/dsa/libcrypto-lib-dsa_check.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_check.o ...\n18.914  sh               579645 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n18.931  powerpc64le-lin  579647 579645   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n18.958  touch            579651 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_digest.d.tmp\n18.960  cc1              579652 579647   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/ess/libcrypto-lib-ess_lib.d -MF crypto/ess/libcrypto-lib-ess_lib.d.tmp -MQ crypto/ess/libcrypto-lib-ess_lib.o -D_REENTRANT -D ...\n18.966  sh               579653 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d > /dev/null 2> /dev/null; then \\\\n\trm \n18.968  cmp              579654 579653   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d\n18.983  mv               579658 579653   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_digest.d.tmp crypto/engine/libcrypto-lib-tb_digest.d\n18.991  as               579650 579155   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-eng_table.o /tmp/ccJbx9tc.s\n18.999  touch            579659 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_md4.d.tmp\n19.009  sh               579661 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.012  cmp              579663 579661   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d\n19.012  sh               579662 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.018  as               579665 579382   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_group_params.o /tmp/ccETYzmu.s ...\n19.025  mv               579666 579661   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_md4.d.tmp crypto/evp/libcrypto-lib-legacy_md4.d\n19.030  sh               579667 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.033  powerpc64le-lin  579664 579662   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.043  as               579669 579119   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-kem.o /tmp/cckwspjs.s\n19.047  aarch64-linux-g  579668 579667   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.051  as               579671 579331   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_asn1.o /tmp/ccpFtpNi.s ...\n19.060  touch            579674 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_group_params.d.tmp\n19.060  as               579673 579406   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_md5_sha1.o /tmp/cciSmI68.s\n19.067  cc1              579675 579668   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p5_crpt.d -MF crypto/evp/libcrypto-lib-p5_crpt.d.tmp -MQ crypto/evp/libcrypto-lib-p5_crpt.o -D_REENTRANT -D ...\n19.073  touch            579676 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp\n19.080  sh               579677 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d > /dev/null 2> /dev/null; then \\\\n\n19.084  touch            579678 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_asn1.d.tmp\n19.086  cmp              579679 579677   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d\n19.092  sh               579682 564020   0 \n19.095  mv               579681 579677   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_group_params.d.tmp crypto/dh/libcrypto-lib-dh_group_params.d\n19.096  sh               579680 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n19.100  cmp              579684 579680   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d\n19.108  sh               579688 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.113  riscv64-linux-g  579689 579688   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.114  mv               579687 579680   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_asn1.d.tmp crypto/dh/libcrypto-lib-dh_asn1.d\n19.120  cc1              579690 579689   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_depr.d -MF crypto/dsa/libcrypto-lib-dsa_depr.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_depr.o ...\n19.122  touch            579691 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-eng_table.d.tmp\n19.131  sh               579692 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d > /dev/null 2> /dev/null; then \\\\n\trm \n19.133  cmp              579683 579682   0 /usr/bin/cmp crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp crypto/evp/libcrypto-lib-keymgmt_lib.d\n19.135  touch            579693 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp\n19.137  cmp              579695 579692   0 /usr/bin/cmp crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d\n19.141  cc1              579672 579664   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-asymcipher.d -MF crypto/evp/libcrypto-lib-asymcipher.d.tmp -MQ crypto/evp/libcrypto-lib-asymcipher.o -D_REENTRANT -D ...\n19.145  sh               579694 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.153  mv               579696 579692   0 /usr/bin/mv crypto/engine/libcrypto-lib-eng_table.d.tmp crypto/engine/libcrypto-lib-eng_table.d\n19.153  riscv64-linux-g  579698 579694   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.157  sh               579697 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d > /dev/null 2> /dev/null; then \n19.165  mv               579699 579682   0 /usr/bin/mv crypto/evp/libcrypto-lib-keymgmt_lib.d.tmp crypto/evp/libcrypto-lib-keymgmt_lib.d\n19.169  cmp              579701 579697   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d\n19.170  cc1              579702 579698   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_err.d -MF crypto/dsa/libcrypto-lib-dsa_err.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_err.o ...\n19.191  mv               579706 579697   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_md5_sha1.d.tmp crypto/evp/libcrypto-lib-legacy_md5_sha1.d\n19.192  sh               579707 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.195  as               579705 579347   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_backend.o /tmp/cc7wiMqw.s ...\n19.196  as               579708 579470   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_blocks.o /tmp/ccH7bth2.s\n19.198  sh               579704 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.200  aarch64-linux-g  579709 579707   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.201  as               579710 579371   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_gen.o /tmp/ccRIA1d6.s ...\n19.210  as               579712 579418   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_meth.o /tmp/ccmfJaXa.s ...\n19.212  as               579711 579481   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_wp.o /tmp/ccKB62gP.s\n19.218  powerpc64le-lin  579714 579704   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.220  as               579713 579320   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_eckey.o /tmp/ccPHrDRF.s\n19.228  touch            579715 564995   0 /usr/bin/touch crypto/err/libcrypto-lib-err_blocks.d.tmp\n19.232  touch            579718 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_backend.d.tmp\n19.235  as               579717 579265   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_dsa.o /tmp/ccIMIjDw.s\n19.235  cc1              579719 579709   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p5_crpt2.d -MF crypto/evp/libcrypto-lib-p5_crpt2.d.tmp -MQ crypto/evp/libcrypto-lib-p5_crpt2.o -D_REENTRANT -D ...\n19.239  sh               579721 564995   0 /bin/sh -c if cmp crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d > /dev/null 2> /dev/null; then \\\\n\trm -f c\n19.239  cc1              579720 579714   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_b64.d -MF crypto/evp/libcrypto-lib-bio_b64.d.tmp -MQ crypto/evp/libcrypto-lib-bio_b64.o -D_REENTRANT -D ...\n19.254  sh               579723 567660   0 \n19.256  cmp              579722 579721   0 /usr/bin/cmp crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d\n19.256  touch            579724 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_gen.d.tmp\n19.260  as               579726 579626   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/ess/libcrypto-lib-ess_err.o /tmp/ccq7rI7L.s\n19.260  touch            579728 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_meth.d.tmp\n19.262  sh               579727 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.273  aarch64-linux-g  579730 579727   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.283  mv               579732 579721   0 /usr/bin/mv crypto/err/libcrypto-lib-err_blocks.d.tmp crypto/err/libcrypto-lib-err_blocks.d\n19.289  cc1              579731 579730   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_dec.d -MF crypto/evp/libcrypto-lib-p_dec.d.tmp -MQ crypto/evp/libcrypto-lib-p_dec.o -D_REENTRANT -D ...\n19.292  touch            579733 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_dsa.d.tmp\n19.292  touch            579734 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-kem.d.tmp\n19.300  touch            579735 564995   0 /usr/bin/touch crypto/ess/libcrypto-lib-ess_err.d.tmp\n19.305  sh               579736 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.306  sh               579729 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh\n19.312  sh               579737 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/dh/l\n19.315  sh               579738 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.317  cmp              579740 579729   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d\n19.318  cmp              579725 579723   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_backend.d.tmp crypto/dh/libcrypto-lib-dh_backend.d\n19.322  touch            579742 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_eckey.d.tmp\n19.322  cmp              579741 579737   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d\n19.325  as               579743 578934   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-exchange.o /tmp/cc8y5pFr.s\n19.325  cmp              579739 579736   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d\n19.328  sh               579744 564995   0 /bin/sh -c if cmp crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.329  powerpc64le-lin  579745 579738   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.336  cmp              579749 579744   0 /usr/bin/cmp crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d\n19.337  mv               579747 579729   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_meth.d.tmp crypto/dh/libcrypto-lib-dh_meth.d\n19.339  mv               579746 579723   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_backend.d.tmp crypto/dh/libcrypto-lib-dh_backend.d\n19.342  sh               579750 564995   0 /bin/sh -c if cmp crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n19.346  mv               579753 579737   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_gen.d.tmp crypto/dh/libcrypto-lib-dh_gen.d\n19.347  mv               579755 579744   0 /usr/bin/mv crypto/ess/libcrypto-lib-ess_err.d.tmp crypto/ess/libcrypto-lib-ess_err.d\n19.350  cc1              579757 579745   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_enc.d -MF crypto/evp/libcrypto-lib-bio_enc.d.tmp -MQ crypto/evp/libcrypto-lib-bio_enc.o -D_REENTRANT -D ...\n19.352  mv               579754 579736   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_dsa.d.tmp crypto/engine/libcrypto-lib-tb_dsa.d\n19.355  cmp              579758 579750   0 /usr/bin/cmp crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d\n19.356  sh               579761 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.358  sh               579748 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/evp/libc\n19.360  cmp              579762 579748   0 /usr/bin/cmp crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d\n19.360  as               579760 579452   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-legacy_sha.o /tmp/ccD4odSB.s\n19.361  as               579756 579381   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_rand.o /tmp/ccHs3Z5e.s\n19.365  riscv64-linux-g  579763 579761   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.368  mv               579764 579750   0 /usr/bin/mv crypto/engine/libcrypto-lib-tb_eckey.d.tmp crypto/engine/libcrypto-lib-tb_eckey.d\n19.376  cc1              579767 579763   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_gen.d -MF crypto/dsa/libcrypto-lib-dsa_gen.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_gen.o ...\n19.376  sh               579766 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.378  powerpc64le-lin  579770 579766   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.380  touch            579768 564020   0 /usr/bin/touch crypto/evp/libcrypto-lib-legacy_wp.d.tmp\n19.389  sh               579771 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.391  mv               579769 579748   0 /usr/bin/mv crypto/evp/libcrypto-lib-kem.d.tmp crypto/evp/libcrypto-lib-kem.d\n19.391  sh               579774 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.395  cc1              579773 579770   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_md.d -MF crypto/evp/libcrypto-lib-bio_md.d.tmp -MQ crypto/evp/libcrypto-lib-bio_md.o -D_REENTRANT -D ...\n19.395  as               579772 579441   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_pmeth.o /tmp/ccSTec0i.s ...\n19.398  sh               579778 564020   0 /bin/sh -c if cmp crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d > /dev/null 2> /dev/null; then \\\\n\trm -f cry\n19.404  powerpc64le-lin  579775 579771   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.404  cmp              579779 579778   0 /usr/bin/cmp crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d\n19.408  as               579781 579181   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_ameth.o /tmp/ccjmrbCz.s ...\n19.409  mv               579780 579778   0 /usr/bin/mv crypto/evp/libcrypto-lib-legacy_wp.d.tmp crypto/evp/libcrypto-lib-legacy_wp.d\n19.413  sh               579777 564995   0 /bin/sh -c powerpc64le-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DECP_NISTZ25\n19.416  riscv64-linux-g  579776 579774   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.418  sh               579782 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.419  powerpc64le-lin  579784 579777   0 /usr/bin/powerpc64le-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DECP_NISTZ256_ASM -DKECCAK1600_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSTATIC_LEGACY -DVPAES_ASM -DX25519_ASM -fPIC -pthread -m64 ...\n19.427  aarch64-linux-g  579785 579782   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.433  cc1              579787 579784   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-c_allc.d -MF crypto/evp/libcrypto-lib-c_allc.d.tmp -MQ crypto/evp/libcrypto-lib-c_allc.o -D_REENTRANT -D ...\n19.433  cc1              579786 579776   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_key.d -MF crypto/dsa/libcrypto-lib-dsa_key.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_key.o ...\n19.437  cc1              579789 579775   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch powerpc64le-linux-gnu -MMD crypto/evp/libcrypto-lib-bio_ok.d -MF crypto/evp/libcrypto-lib-bio_ok.d.tmp -MQ crypto/evp/libcrypto-lib-bio_ok.o -D_REENTRANT -D ...\n19.440  as               579792 579387   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/engine/libcrypto-lib-tb_rsa.o /tmp/ccdQXr0I.s\n19.443  as               579790 579475   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -a64 -mpower8 -many -mlittle --noexecstack -o crypto/err/libcrypto-lib-err_mark.o /tmp/ccSwUwCo.s\n19.443  sh               579794 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.446  sh               579788 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n19.449  as               579793 579392   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_lib.o /tmp/ccWDkEhv.s ...\n19.450  cc1              579791 579785   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_enc.d -MF crypto/evp/libcrypto-lib-p_enc.d.tmp -MQ crypto/evp/libcrypto-lib-p_enc.o -D_REENTRANT -D ...\n19.451  riscv64-linux-g  579796 579794   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.453  touch            579797 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_ameth.d.tmp\n19.463  sh               579801 567660   0 /bin/sh -c if cmp crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n19.463  as               579798 578905   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/evp/libcrypto-lib-evp_rand.o /tmp/ccuww5qj.s\n19.468  as               579802 579495   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 --noexecstack -o crypto/dh/libcrypto-lib-dh_prn.o /tmp/cchSsnk0.s ...\n19.469  cmp              579803 579801   0 /usr/bin/cmp crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d\n19.477  cc1              579800 579796   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_lib.d -MF crypto/dsa/libcrypto-lib-dsa_lib.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_lib.o ...\n19.478  mv               579805 579801   0 /usr/bin/mv crypto/dh/libcrypto-lib-dh_ameth.d.tmp crypto/dh/libcrypto-lib-dh_ameth.d\n19.483  aarch64-linux-g  579799 579788   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n19.487  sh               579808 567660   0 /bin/sh -c riscv64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DAES_ASM -DGHASH_ASM -DINC\n19.490  cc1              579809 579799   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/evp/libcrypto-lib-p_legacy.d -MF crypto/evp/libcrypto-lib-p_legacy.d.tmp -MQ crypto/evp/libcrypto-lib-p_legacy.o -D_REENTRANT -D ...\n19.497  riscv64-linux-g  579810 579808   0 /usr/bin/riscv64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DAES_ASM -DGHASH_ASM -DINCLUDE_C_CHACHA20 -DINCLUDE_C_SHA256 -DINCLUDE_C_SHA512 -DMD5_ASM -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -fPIC -pthread -Wa,--noexecstack ...\n19.503  cc1              579812 579810   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultilib . -imultiarch riscv64-linux-gnu -MMD crypto/dsa/libcrypto-lib-dsa_meth.d -MF crypto/dsa/libcrypto-lib-dsa_meth.d.tmp -MQ crypto/dsa/libcrypto-lib-dsa_meth.o ...\n19.505  touch            579806 564995   0 /usr/bin/touch crypto/engine/libcrypto-lib-tb_rand.d.tmp\n19.505  touch            579811 567660   0 /usr/bin/touch crypto/dh/libcrypto-lib-dh_prn.d.tmp\n"
    },
    {
      "argv": [
        "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 572440,
      "build_script_target_dir": "dlmalloc-e249455d30ed6cef",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
      "pid": 572440,
      "ppid": 572351,
      "root_cargo_pid": 572351,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 572513,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 572513,
      "ppid": 572351,
      "root_cargo_pid": 572351,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 572513,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 572514,
      "ppid": 572513,
      "root_cargo_pid": 572351,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "dlmalloc",
      "cwd": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "event_id": "bsrun:7b072982c1151f5c:8de3aa913df56e91:cbf50263c00d1646",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/dlmalloc-e249455d30ed6cef/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
      "out_dir": "/target/debug/build/dlmalloc-e249455d30ed6cef/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
      "success": true,
      "target": null,
      "version": "0.2.4",
      "_owner": {
        "crate": "dlmalloc",
        "version": "0.2.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4#dlmalloc@0.2.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-aef9vquq/src/dlmalloc-0.2.4",
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
      "build_script_root_pid": 572513,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 572514,
      "ppid": 572513,
      "root_cargo_pid": 572351,
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
