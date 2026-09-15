# `proc-macro2-diagnostics` `0.10.1`

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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
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
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
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
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-133648-1783993035991520599.map",
  "pid": 133648,
  "ppid": 133630,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-133648-1783993035991520599.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
      "name": "equivalent",
      "version": "1.0.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
      "name": "glob",
      "version": "0.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.17.1",
      "name": "hashbrown",
      "version": "0.17.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.14.0",
      "name": "indexmap",
      "version": "2.14.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
      "name": "itoa",
      "version": "1.0.18",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
      "name": "proc-macro2-diagnostics",
      "version": "0.10.1",
      "manifest_path": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
      "name": "serde_json",
      "version": "1.0.150",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.1.1",
      "name": "serde_spanned",
      "version": "1.1.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@1.0.0",
      "name": "target-triple",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
      "name": "termcolor",
      "version": "1.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@1.1.2+spec-1.1.0",
      "name": "toml",
      "version": "1.1.2+spec-1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@1.1.1+spec-1.1.0",
      "name": "toml_datetime",
      "version": "1.1.1+spec-1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.1.2+spec-1.1.0",
      "name": "toml_parser",
      "version": "1.1.2+spec-1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.1.1+spec-1.1.0",
      "name": "toml_writer",
      "version": "1.1.1+spec-1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.118",
      "name": "trybuild",
      "version": "1.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
      "name": "version_check",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
      "name": "winapi-util",
      "version": "0.1.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
      "name": "windows-link",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
      "name": "windows-sys",
      "version": "0.61.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@1.0.4",
      "name": "winnow",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#yansi@1.0.1",
      "name": "yansi",
      "version": "1.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
      "name": "zmij",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
    }
  ],
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "exit_code": 0,
  "kind": "exec",
  "pid": 133572,
  "ppid": 133543,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "quote",
  "cargo_pkg_version": "1.0.46",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "event_id": "used:cc:6213a6aa769d0cd3:39de73edd835a0e7:90b5b7053e564fc9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
  "path": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
  "pid": 133572,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "quote",
  "cargo_pkg_version": "1.0.46",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "event_id": "used:cc:6213a6aa769d0cd3:95f0b394873f4981:90b5b7053e564fc9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
  "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
  "pid": 133572,
  "sha256": "8dfbfb3bc05805f2d30f6b135d136b48e6f8fea08b6af110cec961ba982168c7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "quote",
  "cargo_pkg_version": "1.0.46",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "event_id": "used:cc:6213a6aa769d0cd3:efc627472af82719:90b5b7053e564fc9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
  "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
  "pid": 133572,
  "sha256": "9e88df82d70b457d6be3e9ab1888c0b8cc67c751afce9668ebf84d90dc122bbe",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
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
  "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "cargo_pkg_name": "quote",
  "cargo_pkg_version": "1.0.46",
  "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 133572,
  "ppid": 133543,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO",
    "/target/debug/build/quote-c09a40bfdaa87378",
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
      "directory": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO",
      "kind": "object",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/quote-c09a40bfdaa87378",
      "kind": "object",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/quote-c09a40bfdaa87378",
      "kind": "object",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-133572-1783993035871208686.map",
  "pid": 133572,
  "ppid": 133543,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-133572-1783993035871208686.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "exit_code": 0,
  "kind": "exec",
  "pid": 133579,
  "ppid": 133540,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2",
  "cargo_pkg_version": "1.0.106",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "event_id": "used:cc:b9442a0a5ddbc483:72a5db2712737452:f7fc97f11efd7f4e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
  "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
  "pid": 133579,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2",
  "cargo_pkg_version": "1.0.106",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "event_id": "used:cc:b9442a0a5ddbc483:550a8396f2e8fe00:f7fc97f11efd7f4e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
  "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
  "pid": 133579,
  "sha256": "3fffb761de96669bf3a857803bd35ad9de99b8bac13e437ce02960b8b55c5bb4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2",
  "cargo_pkg_version": "1.0.106",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "event_id": "used:cc:b9442a0a5ddbc483:e2ee294f29d4b703:f7fc97f11efd7f4e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
  "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
  "pid": 133579,
  "sha256": "ce96e069e194b3b3c2e35e729d9874e8098474368d27eb50eaf5f53b5c39bfea",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2",
  "cargo_pkg_version": "1.0.106",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "event_id": "used:cc:b9442a0a5ddbc483:7f56b0437e4311f8:f7fc97f11efd7f4e",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
  "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
  "pid": 133579,
  "sha256": "e9fd8e25458c7fc7531af57b8734f51f366e9ef21c90d90286dad81bfaa65cc3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
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
  "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "cargo_pkg_name": "proc-macro2",
  "cargo_pkg_version": "1.0.106",
  "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 133579,
  "ppid": 133540,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH",
    "/target/debug/build/proc-macro2-3d1201f1e2c08588",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "/lib/x86_64-linux-gnu",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
    "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588"
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
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.gcc_except_table._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.gcc_except_table._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr114drop_in_place$LT$core..option..Option$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h705fb9a475013850E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr114drop_in_place$LT$core..option..Option$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h705fb9a475013850E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr86drop_in_place$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$17h837a0256a2481b8eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr86drop_in_place$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$17h837a0256a2481b8eE",
      "source": "link_map"
    },
    {
      "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN99_$LT$core..iter..sources..once..Once$LT$T$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h7894599ffd4b6a0eE",
      "source": "link_map"
    },
    {
      "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
      "kind": "dynamic_library",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN99_$LT$core..iter..sources..once..Once$LT$T$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h7894599ffd4b6a0eE",
      "source": "link_map"
    }
  ],
  "kind": "resolved_link",
  "map_path": "/tmp/native-trace-link-cc-133579-1783993035885160348.map",
  "pid": 133579,
  "ppid": 133540,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-133579-1783993035885160348.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 133648,
  "ppid": 133630,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:f9e1e0fbbdac1e9e:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
  "pid": 133648,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:7397ff0ac19d4aa0:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "4d34da1d3bd54d2309353f59dfcc2ac89998ce8815adabba6b7eb3a362408236",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:e3f68d9f5b347112:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "db64ed92944a1f9ecad28155447eb863f4456d563fbc19d0ff93109c4879aa9e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:edde6f3fcaad0846:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "5628ad9749896b58d95b8f9fcad140a9eff3318c214fa4a18f44ea826fa79144",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:f5b49166619a7ac2:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "0b2fe44583e0d4d500e19aa0fbffb8ba858895fc91b484d9f03267c008f04e94",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 23

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:5f61b92c1d2058c9:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "83132c2f10cdbec6746157f3218c6965465e53ae1de66015647978b74b0ddc09",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 24

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:f5b0ea2d87892e74:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "9a0e7570ef906beda663e522e6458c916b079a200c75fa448722392847b704b7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 25

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "used:cc:e9be6377eb919435:670009ef91660c49:c241a6194d664f9f",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
  "pid": 133648,
  "sha256": "661eccf3f6b9ed188da8b2d5d98b55c5cc85b0766a25c9f56076fc3caf4d4a68",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
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
  "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "cargo_pkg_name": "proc-macro2-diagnostics",
  "cargo_pkg_version": "0.10.1",
  "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 133648,
  "ppid": 133630,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 28

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
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
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
      "kind": "object",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-133648-1783993035991520599.map",
  "pid": 133648,
  "ppid": 133630,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-133648-1783993035991520599.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

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

#### Record 30

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 1053,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1054,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.625  cc               138226 138222   0 /usr/bin/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcSLBmJJ/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.628  collect2         138227 138226   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.630  ld.lld           138228 138227   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f ...\n13.632  rust-lld         138228 138227   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.678  build-script-bu  138247 137923   0 /target/debug/build/lock_api-abdc83643458130f/build-script-build\n13.680  rustc            138248 138247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n13.691  rustc            138250 138247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/lock_api-2f15a76207848e37/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n13.712  rustc            138258 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n13.824  rustc            138268 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n13.856  rustc            138279 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=8d233e2889d786b0 ...\n13.931  rustc            138292 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n13.954  rustc            138301 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n14.397  runc             138311 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1198069581 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.402  exe              138318 138311   0 /proc/self/exe init\n14.421  curl             138321 138311   0 /usr/bin/curl -f http://localhost:9091/healthz\n14.750  cross            138328 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n14.752  rustc            138331 138328   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.757  rustc            138331 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.769  rustc            138343 138328   0 /home/xmoe/.cargo/bin/rustc -vV\n14.774  rustc            138343 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.784  cargo            138353 138328   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.790  cargo            138353 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.800  rustc            138362 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.809  rustc            138364 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.822  rustc            138368 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.836  rustc            138372 138328   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.842  rustc            138372 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.853  docker           138384 138328   0 /usr/bin/docker --help\n14.865  docker           138395 138328   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.877  runc             138405 1599     0 /usr/bin/runc --version\n14.880  docker-init      138411 1599     0 /usr/bin/docker-init --version\n14.881  docker           138412 138328   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.892  runc             138422 1599     0 /usr/bin/runc --version\n14.895  docker-init      138428 1599     0 /usr/bin/docker-init --version\n14.918  rustup           138429 138328   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.925  rustup           138438 138328   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.947  rustup           138447 138328   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.971  uname            138456 138328   0 /usr/bin/uname -r\n14.979  runc             138458 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup kill --all 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d 9\n14.987  runc             138464 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup delete 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n14.988  docker           138466 138328   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.039  systemd-sysctl   138485 138483   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe84a127 --prefix=/net/ipv4/neigh/vethe84a127 --prefix=/net/ipv6/conf/vethe84a127 --prefix=/net/ipv6/neigh/vethe84a127\n15.041  systemd-sysctl   138486 138484   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0fbca5d --prefix=/net/ipv4/neigh/veth0fbca5d --prefix=/net/ipv6/conf/veth0fbca5d --prefix=/net/ipv6/neigh/veth0fbca5d\n15.053  containerd-shim  138514 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 start\n15.057  containerd-shim  138525 138514   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 -address /var/run/docker/containerd/containerd.sock\n15.062  runc             138535 138525   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7\n15.068  exe              138543 138535   0 /proc/self/exe init\n15.105  exe              138552 138535   0 /proc/1599/exe -exec-root=/var/run/docker ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 d7da31e8f8e1\n15.124  exe              138560 1599     0 /proc/self/exe /var/run/docker/netns/fd7aeea2debc all false\n15.171  runc             138579 138525   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --log-format json --systemd-cgroup start ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7\n15.176  sh               138546 138525   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.177  cargo            138585 138546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.183  containerd-shim  138588 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 delete\n15.185  runc             138595 138588   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6 --log-format json delete --force 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n15.189  cargo-native-tr  138585 138546   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.192  cargo            138600 138585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.203  rustc            138601 138600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.214  rustc            138603 138600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.218  systemd-sysctl   138604 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac98c9a --prefix=/net/ipv4/neigh/vethac98c9a --prefix=/net/ipv6/conf/vethac98c9a --prefix=/net/ipv6/neigh/vethac98c9a\n15.229  execsnoop        138610 138585   0 /usr/local/bin/execsnoop -t\n15.231  python3          138610 138585   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.400  cross            138621 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.403  cross            138622 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.403  rustc            138627 138622   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.403  rustc            138628 138621   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.408  rustc            138628 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.411  rustc            138627 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.423  rustc            138651 138621   0 /home/xmoe/.cargo/bin/rustc -vV\n15.429  rustc            138661 138622   0 /home/xmoe/.cargo/bin/rustc -vV\n15.431  rustc            138651 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.438  rustc            138661 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.446  cargo            138672 138621   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.450  cargo            138674 138622   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.454  cargo            138672 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.463  cargo            138674 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.470  rustc            138693 138672   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.475  rustc            138694 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.485  rustc            138697 138672   0 \n15.488  rustc            138698 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.501  rustc            138705 138672   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.502  rustc            138706 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.519  rustc            138715 138621   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.521  rustc            138716 138622   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.529  rustc            138715 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.531  rustc            138716 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.539  runc             138733 117959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 --log-format json --systemd-cgroup kill --all e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7 9\n15.547  docker           138745 138621   0 /usr/bin/docker --help\n15.549  docker           138746 138622   0 /usr/bin/docker --help\n15.564  runc             138765 117959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 --log-format json --systemd-cgroup delete e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7\n15.569  docker           138771 138621   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.574  docker           138777 138622   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.593  runc             138791 1599     0 /usr/bin/runc --version\n15.596  runc             138792 1599     0 /usr/bin/runc --version\n15.600  docker-init      138804 1599     0 /usr/bin/docker-init --version\n15.601  docker-init      138805 1599     0 /usr/bin/docker-init --version\n15.604  docker           138806 138622   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.605  docker           138807 138621   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.630  runc             138824 1599     0 /usr/bin/runc --version\n15.632  runc             138825 1599     0 /usr/bin/runc --version\n15.636  docker-init      138838 1599     0 /usr/bin/docker-init --version\n15.641  docker-init      138839 1599     0 /usr/bin/docker-init --version\n15.679  rustup           138841 138622   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.683  rustup           138843 138621   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.690  rustup           138860 138622   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.695  rustup           138865 138621   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.735  rustup           138879 138622   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.738  rustup           138880 138621   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.775  containerd-shim  138899 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 delete\n15.780  runc             138906 138899   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b --log-format json delete --force e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7\n15.785  uname            138907 138622   0 /usr/bin/uname -r\n15.789  uname            138912 138621   0 \n15.813  docker           138914 138622   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.816  docker           138920 138621   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.821  systemd-sysctl   138926 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe870e32 --prefix=/net/ipv4/neigh/vethe870e32 --prefix=/net/ipv6/conf/vethe870e32 --prefix=/net/ipv6/neigh/vethe870e32\n15.875  systemd-sysctl   138941 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9a6b8e3 --prefix=/net/ipv4/neigh/veth9a6b8e3 --prefix=/net/ipv6/conf/veth9a6b8e3 --prefix=/net/ipv6/neigh/veth9a6b8e3\n15.877  systemd-sysctl   138942 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth312c79a --prefix=/net/ipv4/neigh/veth312c79a --prefix=/net/ipv6/conf/veth312c79a --prefix=/net/ipv6/neigh/veth312c79a\n15.922  rustc            138945 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.59/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n15.934  systemd-sysctl   138949 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21d14a9 --prefix=/net/ipv4/neigh/veth21d14a9 --prefix=/net/ipv6/conf/veth21d14a9 --prefix=/net/ipv6/neigh/veth21d14a9\n15.934  systemd-sysctl   138948 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb741ae8 --prefix=/net/ipv4/neigh/vethb741ae8 --prefix=/net/ipv6/conf/vethb741ae8 --prefix=/net/ipv6/neigh/vethb741ae8\n15.950  containerd-shim  138952 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d start\n15.956  containerd-shim  138958 138952   0 \n15.962  runc             138968 138958   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d\n15.962  containerd-shim  138969 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e start\n15.969  containerd-shim  138982 138969   0 \n15.972  exe              138992 138968   0 /proc/self/exe init\n15.974  runc             138994 138982   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e\n15.981  exe              139002 138994   0 /proc/self/exe init\n16.018  exe              139019 138968   0 /proc/1599/exe -exec-root=/var/run/docker d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d d7da31e8f8e1\n16.023  exe              139025 138994   0 /proc/1599/exe -exec-root=/var/run/docker 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e d7da31e8f8e1\n16.055  exe              139036 1599     0 /proc/self/exe /var/run/docker/netns/293d9778fcc8 all false\n16.071  exe              139045 1599     0 /proc/self/exe /var/run/docker/netns/717e2f168ea8 all false\n16.115  runc             139064 138958   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --log-format json --systemd-cgroup start d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d\n16.122  sh               139006 138958   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.123  cargo            139070 139006   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.136  runc             139072 138982   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --log-format json --systemd-cgroup start 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e\n16.141  cargo-native-tr  139070 139006   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.144  sh               139013 138982   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.148  cargo            139079 139013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.148  cargo            139078 139070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.158  cargo-native-tr  139079 139013   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.162  cargo            139082 139079   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.163  rustc            139081 139078   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.174  rustc            139084 139082   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.178  rustc            139085 139078   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.186  rustc            139087 139082   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.194  execsnoop        139092 139070   0 /usr/local/bin/execsnoop -t\n16.194  python3          139092 139070   0 \n16.203  execsnoop        139097 139079   0 /usr/local/bin/execsnoop -t\n16.204  python3          139097 139079   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.509  runc             139113 119243   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 --log-format json --systemd-cgroup kill --all 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d 9\n16.527  runc             139121 119243   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 --log-format json --systemd-cgroup delete 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d\n16.590  cc               139130 138945   0 /tmp/native-trace-137337-1783993046182/shims/cc -Wl,--version-script=/target/debug/deps/rustcv5jtOP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv5jtOP/symbols.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.14.rcgu.o ...\n16.591  cc               139131 139130   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcv5jtOP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv5jtOP/symbols.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.14.rcgu.o ...\n16.593  collect2         139132 139131   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv5jtOP/raw-dylibs ...\n16.595  ld.lld           139133 139132   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv5jtOP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.596  rust-lld         139133 139132   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.625  runc             139150 119322   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c --log-format json --systemd-cgroup kill --all eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced 9\n16.643  runc             139156 119322   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c --log-format json --systemd-cgroup delete eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced\n16.703  containerd-shim  139163 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 delete\n16.706  runc             139170 139163   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929 --log-format json delete --force 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d\n16.726  rustc            139177 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.59/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=171bc390f5653ae1 ...\n16.742  systemd-sysctl   139181 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2374113 --prefix=/net/ipv4/neigh/veth2374113 --prefix=/net/ipv6/conf/veth2374113 --prefix=/net/ipv6/neigh/veth2374113\n16.753  rustc            139186 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"protobuf\" --check-cfg cfg(docsrs,test) ...\n16.843  containerd-shim  139190 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c delete\n16.846  runc             139197 139190   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ce --log-format json delete --force eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced\n16.880  systemd-sysctl   139202 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha5668f0 --prefix=/net/ipv4/neigh/vetha5668f0 --prefix=/net/ipv6/conf/vetha5668f0 --prefix=/net/ipv6/neigh/vetha5668f0\n17.184  sh               139203 2147557   0 /bin/sh -c which ps\n17.186  which            139203 2147557   0 /usr/bin/which ps\n17.188  sh               139204 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.189  ps               139204 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.214  sh               139205 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.216  cpuUsage.sh      139205 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.217  sed              139206 139205   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.219  cat              139207 139205   0 /usr/bin/cat /proc/2240539/stat\n17.221  cat              139208 139205   0 /usr/bin/cat /proc/4193716/stat\n17.222  sleep            139209 139205   0 /usr/bin/sleep 1\n17.274  git              139210 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.929  cargo            139375 138585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.941  rustc            139376 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.957  rustc            139382 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.049  cc               139430 139382   0 /tmp/native-trace-138585-1783993050827/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc0UvATj/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1ngq6ad.rcgu.o ...\n18.050  cc               139431 139430   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc0UvATj/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1ngq6ad.rcgu.o ...\n18.053  collect2         139432 139431   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.055  ld.lld           139433 139432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.056  rust-lld         139433 139432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.106  build-script-bu  139451 139375   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.107  rustc            139452 139451   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.120  rustc            139455 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9a2474cc3d7283b6 ...\n18.224  sed              139462 139205   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.226  cat              139463 139205   0 /usr/bin/cat /proc/2240539/stat\n18.228  cat              139465 139205   0 /usr/bin/cat /proc/4193716/stat\n18.272  cargo            139467 139070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.285  rustc            139468 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.304  rustc            139475 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.312  cargo            139477 139079   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.313  git              139476 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n18.325  rustc            139481 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.341  rustc            139487 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.388  cc               139535 139475   0 /tmp/native-trace-139070-1783993051779/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustcTmBawo/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1a96nkb.rcgu.o ...\n18.389  cc               139536 139535   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustcTmBawo/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1a96nkb.rcgu.o ...\n18.393  collect2         139539 139536   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.394  ld.lld           139540 139539   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.396  rust-lld         139540 139539   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.429  cc               139599 139487   0 /tmp/native-trace-139079-1783993051796/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc94wMcA/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.0ql1bhj.rcgu.o ...\n18.429  cc               139600 139599   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc94wMcA/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.0ql1bhj.rcgu.o ...\n18.433  collect2         139601 139600   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.434  ld.lld           139602 139601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.435  rust-lld         139602 139601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.449  build-script-bu  139620 139467   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.451  rustc            139621 139620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.463  rustc            139624 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2e81567ac1e8ee66 ...\n18.484  build-script-bu  139632 139477   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.486  rustc            139633 139632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.499  rustc            139636 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=75caea18bd00badc ...\n19.112  cross            139643 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n19.113  rustc            139646 139643   0 /home/xmoe/.cargo/bin/rustc --print target-list\n19.118  rustc            139646 139643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n"
}
```

#### Record 31

```json
{
  "argv": [
    "/target/debug/build/quote-c09a40bfdaa87378/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133619,
  "build_script_target_dir": "quote-c09a40bfdaa87378",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/quote-c09a40bfdaa87378/build-script-build",
  "pid": 133619,
  "ppid": 133530,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "_build_script_out_dir": "/target/debug/build/quote-c09a40bfdaa87378/out"
}
```

#### Record 32

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133619,
  "build_script_target_dir": "quote-c09a40bfdaa87378",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133621,
  "ppid": 133619,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "_build_script_out_dir": "/target/debug/build/quote-c09a40bfdaa87378/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build",
  "pid": 133624,
  "ppid": 133530,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out"
}
```

#### Record 34

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133625,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 35

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133631,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span_location.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133646,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span_file.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133655,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 38

```json
{
  "argv": [
    "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133683,
  "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build",
  "pid": 133683,
  "ppid": 133530,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/out"
}
```

#### Record 39

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133683,
  "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133684,
  "ppid": 133683,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_build_script_out_dir": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 40

```json
{
  "crate": "quote",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "event_id": "bsrun:f98078fec332daf1:1a6a29dd7a1e190e:4757e729dcc8c47e",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/quote-c09a40bfdaa87378/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
  "out_dir": "/target/debug/build/quote-c09a40bfdaa87378/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
  "success": true,
  "target": null,
  "version": "1.0.46",
  "_owner": {
    "crate": "quote",
    "version": "1.0.46",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
    "source": "cwd_prefix"
  }
}
```

#### Record 41

```json
{
  "crate": "proc-macro2",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "event_id": "bsrun:de579e35607e37bb:2fcd632d4d8cac39:4c7913c0d47ce57e",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
  "out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
  "success": true,
  "target": null,
  "version": "1.0.106",
  "_owner": {
    "crate": "proc-macro2",
    "version": "1.0.106",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
    "source": "cwd_prefix"
  }
}
```

#### Record 42

```json
{
  "crate": "proc-macro2-diagnostics",
  "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "event_id": "bsrun:b79cb7451ab038ab:e545dc5618aa31f5:3b8f426181e61f09",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
  "out_dir": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
  "success": true,
  "target": null,
  "version": "0.10.1",
  "_owner": {
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
    "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
    "source": "cwd_prefix"
  }
}
```

#### Record 43

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133619,
  "build_script_target_dir": "quote-c09a40bfdaa87378",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133621,
  "ppid": 133619,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 44

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133625,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 45

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133631,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 46

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span_location.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133646,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 47

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--cfg=procmacro2_build_probe",
    "--edition=2021",
    "--crate-name=proc_macro2",
    "--crate-type=lib",
    "--cap-lints=allow",
    "--emit=dep-info,metadata",
    "--out-dir",
    "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
    "src/probe/proc_macro_span_file.rs",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133624,
  "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133655,
  "ppid": 133624,
  "root_cargo_pid": 133530,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 48

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 133683,
  "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 133684,
  "ppid": 133683,
  "root_cargo_pid": 133530,
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
  "time": "2026-07-14T01:37:35.078511+00:00",
  "crate": "proc-macro2-diagnostics",
  "version": "0.10.1",
  "architecture": "aarch64",
  "duration_seconds": 27.54771206714213,
  "trace_record_count": 42,
  "trace_owner_summary": {
    "owner_package_count": 30,
    "owner_packages": [
      {
        "crate": "toml_datetime",
        "version": "1.1.1+spec-1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@1.1.1+spec-1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0/Cargo.toml"
      },
      {
        "crate": "toml_parser",
        "version": "1.1.2+spec-1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.1.2+spec-1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0/Cargo.toml"
      },
      {
        "crate": "toml_writer",
        "version": "1.1.1+spec-1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.1.1+spec-1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0/Cargo.toml"
      },
      {
        "crate": "toml",
        "version": "1.1.2+spec-1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@1.1.2+spec-1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0/Cargo.toml"
      },
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
        "crate": "serde_spanned",
        "version": "1.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.1.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1/Cargo.toml"
      },
      {
        "crate": "target-triple",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml"
      },
      {
        "crate": "windows-link",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.61.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml"
      },
      {
        "crate": "equivalent",
        "version": "1.0.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml"
      },
      {
        "crate": "hashbrown",
        "version": "0.17.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.17.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1/Cargo.toml"
      },
      {
        "crate": "trybuild",
        "version": "1.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118/Cargo.toml"
      },
      {
        "crate": "indexmap",
        "version": "2.14.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.14.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0/Cargo.toml"
      },
      {
        "crate": "termcolor",
        "version": "1.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "winnow",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "yansi",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#yansi@1.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1/Cargo.toml"
      },
      {
        "crate": "zmij",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml"
      },
      {
        "crate": "glob",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml"
      },
      {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "manifest_path": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 31,
    "unattributed_event_count": 11,
    "owners": [
      {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
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
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "event_count": 9,
        "kind_counts": {
          "exec": 1,
          "used_input": 4,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "event_count": 8,
        "kind_counts": {
          "exec": 1,
          "used_input": 3,
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
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#equivalent@1.0.2",
          "name": "equivalent",
          "version": "1.0.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/equivalent-1.0.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#glob@0.3.3",
          "name": "glob",
          "version": "0.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hashbrown@0.17.1",
          "name": "hashbrown",
          "version": "0.17.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.17.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#indexmap@2.14.0",
          "name": "indexmap",
          "version": "2.14.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/indexmap-2.14.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
          "name": "itoa",
          "version": "1.0.18",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
          "name": "proc-macro2-diagnostics",
          "version": "0.10.1",
          "manifest_path": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
          "name": "serde_json",
          "version": "1.0.150",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_spanned@1.1.1",
          "name": "serde_spanned",
          "version": "1.1.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_spanned-1.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#target-triple@1.0.0",
          "name": "target-triple",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-triple-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#termcolor@1.4.1",
          "name": "termcolor",
          "version": "1.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/termcolor-1.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml@1.1.2+spec-1.1.0",
          "name": "toml",
          "version": "1.1.2+spec-1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml-1.1.2+spec-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_datetime@1.1.1+spec-1.1.0",
          "name": "toml_datetime",
          "version": "1.1.1+spec-1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_datetime-1.1.1+spec-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_parser@1.1.2+spec-1.1.0",
          "name": "toml_parser",
          "version": "1.1.2+spec-1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_parser-1.1.2+spec-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#toml_writer@1.1.1+spec-1.1.0",
          "name": "toml_writer",
          "version": "1.1.1+spec-1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/toml_writer-1.1.1+spec-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#trybuild@1.0.118",
          "name": "trybuild",
          "version": "1.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/trybuild-1.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
          "name": "version_check",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.11",
          "name": "winapi-util",
          "version": "0.1.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-link@0.2.1",
          "name": "windows-link",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-link-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.61.2",
          "name": "windows-sys",
          "version": "0.61.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.61.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winnow@1.0.4",
          "name": "winnow",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winnow-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#yansi@1.0.1",
          "name": "yansi",
          "version": "1.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/yansi-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
          "name": "zmij",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
        }
      ],
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "exit_code": 0,
      "kind": "exec",
      "pid": 133572,
      "ppid": 133543,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "quote",
      "cargo_pkg_version": "1.0.46",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "event_id": "used:cc:6213a6aa769d0cd3:39de73edd835a0e7:90b5b7053e564fc9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
      "pid": 133572,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "quote",
      "cargo_pkg_version": "1.0.46",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "event_id": "used:cc:6213a6aa769d0cd3:95f0b394873f4981:90b5b7053e564fc9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
      "pid": 133572,
      "sha256": "8dfbfb3bc05805f2d30f6b135d136b48e6f8fea08b6af110cec961ba982168c7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "quote",
      "cargo_pkg_version": "1.0.46",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "event_id": "used:cc:6213a6aa769d0cd3:efc627472af82719:90b5b7053e564fc9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
      "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
      "pid": 133572,
      "sha256": "9e88df82d70b457d6be3e9ab1888c0b8cc67c751afce9668ebf84d90dc122bbe",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
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
      "output": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "cargo_pkg_name": "quote",
      "cargo_pkg_version": "1.0.46",
      "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 133572,
      "ppid": 133543,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO",
        "/target/debug/build/quote-c09a40bfdaa87378",
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
          "directory": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO",
          "kind": "object",
          "path": "/target/debug/build/quote-c09a40bfdaa87378/rustcqULdeO/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/quote-c09a40bfdaa87378",
          "kind": "object",
          "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/quote-c09a40bfdaa87378",
          "kind": "object",
          "path": "/target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-133572-1783993035871208686.map",
      "pid": 133572,
      "ppid": 133543,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-133572-1783993035871208686.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "exit_code": 0,
      "kind": "exec",
      "pid": 133579,
      "ppid": 133540,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2",
      "cargo_pkg_version": "1.0.106",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "event_id": "used:cc:b9442a0a5ddbc483:72a5db2712737452:f7fc97f11efd7f4e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
      "pid": 133579,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2",
      "cargo_pkg_version": "1.0.106",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "event_id": "used:cc:b9442a0a5ddbc483:550a8396f2e8fe00:f7fc97f11efd7f4e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
      "pid": 133579,
      "sha256": "3fffb761de96669bf3a857803bd35ad9de99b8bac13e437ce02960b8b55c5bb4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2",
      "cargo_pkg_version": "1.0.106",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "event_id": "used:cc:b9442a0a5ddbc483:e2ee294f29d4b703:f7fc97f11efd7f4e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
      "pid": 133579,
      "sha256": "ce96e069e194b3b3c2e35e729d9874e8098474368d27eb50eaf5f53b5c39bfea",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2",
      "cargo_pkg_version": "1.0.106",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "event_id": "used:cc:b9442a0a5ddbc483:7f56b0437e4311f8:f7fc97f11efd7f4e",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
      "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
      "pid": 133579,
      "sha256": "e9fd8e25458c7fc7531af57b8734f51f366e9ef21c90d90286dad81bfaa65cc3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
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
      "output": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "cargo_pkg_name": "proc-macro2",
      "cargo_pkg_version": "1.0.106",
      "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 133579,
      "ppid": 133540,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH",
        "/target/debug/build/proc-macro2-3d1201f1e2c08588",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "/lib/x86_64-linux-gnu",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
        "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588"
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
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/rustcYATJEH/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o",
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
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/6ba8             6ba8       18     4         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.gcc_except_table._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.gcc_except_table._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22410            22410       3d    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr114drop_in_place$LT$core..option..Option$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h705fb9a475013850E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr114drop_in_place$LT$core..option..Option$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h705fb9a475013850E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22730            22730       54    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr288drop_in_place$LT$core..iter..adapters..chain..Chain$LT$core..iter..adapters..chain..Chain$LT$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$C$core..option..IntoIter$LT$std..ffi..os_str..OsString$GT$$GT$$C$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$$GT$17h9a455f21e826f757E",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/22e20            22e20        c    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr86drop_in_place$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$17h837a0256a2481b8eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN4core3ptr86drop_in_place$LT$core..iter..sources..once..Once$LT$std..ffi..os_str..OsString$GT$$GT$17h837a0256a2481b8eE",
          "source": "link_map"
        },
        {
          "directory": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/24a10            24a10       48    16         /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN99_$LT$core..iter..sources..once..Once$LT$T$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h7894599ffd4b6a0eE",
          "source": "link_map"
        },
        {
          "directory": "/target/debug/build/proc-macro2-3d1201f1e2c08588",
          "kind": "dynamic_library",
          "path": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.rcgu.o:(.text._ZN99_$LT$core..iter..sources..once..Once$LT$T$GT$$u20$as$u20$core..iter..traits..iterator..Iterator$GT$4next17h7894599ffd4b6a0eE",
          "source": "link_map"
        }
      ],
      "kind": "resolved_link",
      "map_path": "/tmp/native-trace-link-cc-133579-1783993035885160348.map",
      "pid": 133579,
      "ppid": 133540,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-133579-1783993035885160348.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 133648,
      "ppid": 133630,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:f9e1e0fbbdac1e9e:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
      "pid": 133648,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:7397ff0ac19d4aa0:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "4d34da1d3bd54d2309353f59dfcc2ac89998ce8815adabba6b7eb3a362408236",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:e3f68d9f5b347112:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "db64ed92944a1f9ecad28155447eb863f4456d563fbc19d0ff93109c4879aa9e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:edde6f3fcaad0846:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "5628ad9749896b58d95b8f9fcad140a9eff3318c214fa4a18f44ea826fa79144",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:f5b49166619a7ac2:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "0b2fe44583e0d4d500e19aa0fbffb8ba858895fc91b484d9f03267c008f04e94",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:5f61b92c1d2058c9:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "83132c2f10cdbec6746157f3218c6965465e53ae1de66015647978b74b0ddc09",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:f5b0ea2d87892e74:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "9a0e7570ef906beda663e522e6458c916b079a200c75fa448722392847b704b7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "used:cc:e9be6377eb919435:670009ef91660c49:c241a6194d664f9f",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
      "pid": 133648,
      "sha256": "661eccf3f6b9ed188da8b2d5d98b55c5cc85b0766a25c9f56076fc3caf4d4a68",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
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
      "output": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "cargo_pkg_name": "proc-macro2-diagnostics",
      "cargo_pkg_version": "0.10.1",
      "context_path": "/tmp/native-trace-132550-1783993033403/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-132550-1783993033403/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 133648,
      "ppid": 133630,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
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
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/rustccGDKvE/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.1fzbpg1jk0z6avarnk45zp18t.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.3n8d6tdd04q15wt8a9sp5h7co.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.4sd8gzfkfm0bka4r8kpq4mt0o.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.5tuk028tl4xbx2ubuhyp35siz.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ch3wi3if5kr0duevu7dv3zuuf.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.don0ymik39ke5v75ubk1r3f1r.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143",
          "kind": "object",
          "path": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build_script_build-a3bc0c613ed5c143.ad7mqejcomc5wws0ejwaevy8l.1rpp2kx.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib(version_check-6524f1f18eb3e9e4.version_check.962a37620f5f842f-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-133648-1783993035991520599.map",
      "pid": 133648,
      "ppid": 133630,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-133648-1783993035991520599.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
      "parsed_event_count": 1053,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1054,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.625  cc               138226 138222   0 /usr/bin/cc -m64 /target/debug/build/lock_api-abdc83643458130f/rustcSLBmJJ/symbols.o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.build_script_build.6b7456c9558868d5-cgu.0.rcgu /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f.7ew9kgwabcu6jaii6ij7si78t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9c48399c200a1a1c.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n13.628  collect2         138227 138226   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.630  ld.lld           138228 138227   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-abdc83643458130f/build_script_build-abdc83643458130f ...\n13.632  rust-lld         138228 138227   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7VzYCc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.678  build-script-bu  138247 137923   0 /target/debug/build/lock_api-abdc83643458130f/build-script-build\n13.680  rustc            138248 138247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n13.691  rustc            138250 138247   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/lock_api-2f15a76207848e37/out --emit=llvm-ir --target powerpc64le-unknown-linux-gnu -\n13.712  rustc            138258 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.12/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"atomic_usize\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n13.824  rustc            138268 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n13.856  rustc            138279 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.10/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=8d233e2889d786b0 ...\n13.931  rustc            138292 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.60/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n13.954  rustc            138301 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n14.397  runc             138311 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1198069581 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.402  exe              138318 138311   0 /proc/self/exe init\n14.421  curl             138321 138311   0 /usr/bin/curl -f http://localhost:9091/healthz\n14.750  cross            138328 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n14.752  rustc            138331 138328   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.757  rustc            138331 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.769  rustc            138343 138328   0 /home/xmoe/.cargo/bin/rustc -vV\n14.774  rustc            138343 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.784  cargo            138353 138328   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.790  cargo            138353 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n14.800  rustc            138362 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.809  rustc            138364 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.822  rustc            138368 138353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.836  rustc            138372 138328   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.842  rustc            138372 138328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.853  docker           138384 138328   0 /usr/bin/docker --help\n14.865  docker           138395 138328   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.877  runc             138405 1599     0 /usr/bin/runc --version\n14.880  docker-init      138411 1599     0 /usr/bin/docker-init --version\n14.881  docker           138412 138328   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.892  runc             138422 1599     0 /usr/bin/runc --version\n14.895  docker-init      138428 1599     0 /usr/bin/docker-init --version\n14.918  rustup           138429 138328   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.925  rustup           138438 138328   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.947  rustup           138447 138328   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.971  uname            138456 138328   0 /usr/bin/uname -r\n14.979  runc             138458 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup kill --all 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d 9\n14.987  runc             138464 130445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 --log-format json --systemd-cgroup delete 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n14.988  docker           138466 138328   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.039  systemd-sysctl   138485 138483   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe84a127 --prefix=/net/ipv4/neigh/vethe84a127 --prefix=/net/ipv6/conf/vethe84a127 --prefix=/net/ipv6/neigh/vethe84a127\n15.041  systemd-sysctl   138486 138484   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0fbca5d --prefix=/net/ipv4/neigh/veth0fbca5d --prefix=/net/ipv6/conf/veth0fbca5d --prefix=/net/ipv6/neigh/veth0fbca5d\n15.053  containerd-shim  138514 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 start\n15.057  containerd-shim  138525 138514   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 -address /var/run/docker/containerd/containerd.sock\n15.062  runc             138535 138525   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7\n15.068  exe              138543 138535   0 /proc/self/exe init\n15.105  exe              138552 138535   0 /proc/1599/exe -exec-root=/var/run/docker ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7 d7da31e8f8e1\n15.124  exe              138560 1599     0 /proc/self/exe /var/run/docker/netns/fd7aeea2debc all false\n15.171  runc             138579 138525   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4 --log-format json --systemd-cgroup start ee167f98c0a2fedd473865509df9747f76fa865196e1e07e9d3587d6bb4572e7\n15.176  sh               138546 138525   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n15.177  cargo            138585 138546   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.183  containerd-shim  138588 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8 delete\n15.185  runc             138595 138588   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6 --log-format json delete --force 1fdbe6c61ad80ece9ef77ed4b9cdfede262866803b3373795033e4231c8c1b6d\n15.189  cargo-native-tr  138585 138546   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n15.192  cargo            138600 138585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n15.203  rustc            138601 138600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.214  rustc            138603 138600   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.218  systemd-sysctl   138604 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethac98c9a --prefix=/net/ipv4/neigh/vethac98c9a --prefix=/net/ipv6/conf/vethac98c9a --prefix=/net/ipv6/neigh/vethac98c9a\n15.229  execsnoop        138610 138585   0 /usr/local/bin/execsnoop -t\n15.231  python3          138610 138585   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.400  cross            138621 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.403  cross            138622 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.403  rustc            138627 138622   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.403  rustc            138628 138621   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.408  rustc            138628 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.411  rustc            138627 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.423  rustc            138651 138621   0 /home/xmoe/.cargo/bin/rustc -vV\n15.429  rustc            138661 138622   0 /home/xmoe/.cargo/bin/rustc -vV\n15.431  rustc            138651 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.438  rustc            138661 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.446  cargo            138672 138621   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.450  cargo            138674 138622   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.454  cargo            138672 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.463  cargo            138674 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.470  rustc            138693 138672   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.475  rustc            138694 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.485  rustc            138697 138672   0 \n15.488  rustc            138698 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.501  rustc            138705 138672   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.502  rustc            138706 138674   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.519  rustc            138715 138621   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.521  rustc            138716 138622   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n15.529  rustc            138715 138621   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.531  rustc            138716 138622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n15.539  runc             138733 117959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 --log-format json --systemd-cgroup kill --all e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7 9\n15.547  docker           138745 138621   0 /usr/bin/docker --help\n15.549  docker           138746 138622   0 /usr/bin/docker --help\n15.564  runc             138765 117959   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 --log-format json --systemd-cgroup delete e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7\n15.569  docker           138771 138621   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.574  docker           138777 138622   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n15.593  runc             138791 1599     0 /usr/bin/runc --version\n15.596  runc             138792 1599     0 /usr/bin/runc --version\n15.600  docker-init      138804 1599     0 /usr/bin/docker-init --version\n15.601  docker-init      138805 1599     0 /usr/bin/docker-init --version\n15.604  docker           138806 138622   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.605  docker           138807 138621   0 /usr/bin/docker info -f {{.SecurityOptions}}\n15.630  runc             138824 1599     0 /usr/bin/runc --version\n15.632  runc             138825 1599     0 /usr/bin/runc --version\n15.636  docker-init      138838 1599     0 /usr/bin/docker-init --version\n15.641  docker-init      138839 1599     0 /usr/bin/docker-init --version\n15.679  rustup           138841 138622   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.683  rustup           138843 138621   0 /home/xmoe/.cargo/bin/rustup toolchain list\n15.690  rustup           138860 138622   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.695  rustup           138865 138621   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n15.735  rustup           138879 138622   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.738  rustup           138880 138621   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.775  containerd-shim  138899 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871 delete\n15.780  runc             138906 138899   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b --log-format json delete --force e8d91e492cf486bd414a4bc89f50d761e7f7279410195e5f9527cf70871cc3b7\n15.785  uname            138907 138622   0 /usr/bin/uname -r\n15.789  uname            138912 138621   0 \n15.813  docker           138914 138622   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.816  docker           138920 138621   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n15.821  systemd-sysctl   138926 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe870e32 --prefix=/net/ipv4/neigh/vethe870e32 --prefix=/net/ipv6/conf/vethe870e32 --prefix=/net/ipv6/neigh/vethe870e32\n15.875  systemd-sysctl   138941 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth9a6b8e3 --prefix=/net/ipv4/neigh/veth9a6b8e3 --prefix=/net/ipv6/conf/veth9a6b8e3 --prefix=/net/ipv6/neigh/veth9a6b8e3\n15.877  systemd-sysctl   138942 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth312c79a --prefix=/net/ipv4/neigh/veth312c79a --prefix=/net/ipv6/conf/veth312c79a --prefix=/net/ipv6/neigh/veth312c79a\n15.922  rustc            138945 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.59/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n15.934  systemd-sysctl   138949 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth21d14a9 --prefix=/net/ipv4/neigh/veth21d14a9 --prefix=/net/ipv6/conf/veth21d14a9 --prefix=/net/ipv6/neigh/veth21d14a9\n15.934  systemd-sysctl   138948 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb741ae8 --prefix=/net/ipv4/neigh/vethb741ae8 --prefix=/net/ipv6/conf/vethb741ae8 --prefix=/net/ipv6/neigh/vethb741ae8\n15.950  containerd-shim  138952 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d start\n15.956  containerd-shim  138958 138952   0 \n15.962  runc             138968 138958   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d\n15.962  containerd-shim  138969 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e start\n15.969  containerd-shim  138982 138969   0 \n15.972  exe              138992 138968   0 /proc/self/exe init\n15.974  runc             138994 138982   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e\n15.981  exe              139002 138994   0 /proc/self/exe init\n16.018  exe              139019 138968   0 /proc/1599/exe -exec-root=/var/run/docker d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d d7da31e8f8e1\n16.023  exe              139025 138994   0 /proc/1599/exe -exec-root=/var/run/docker 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e d7da31e8f8e1\n16.055  exe              139036 1599     0 /proc/self/exe /var/run/docker/netns/293d9778fcc8 all false\n16.071  exe              139045 1599     0 /proc/self/exe /var/run/docker/netns/717e2f168ea8 all false\n16.115  runc             139064 138958   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a0 --log-format json --systemd-cgroup start d0074c65911dd3e3f23ab80adf93058b857ea80cd9b514cf49ab48c73a02fb9d\n16.122  sh               139006 138958   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.123  cargo            139070 139006   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.136  runc             139072 138982   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c --log-format json --systemd-cgroup start 16bd5620aaf5ac5f0895da6d345139b0ed4ae312e91d06e27555930fc5c83b5e\n16.141  cargo-native-tr  139070 139006   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.144  sh               139013 138982   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.148  cargo            139079 139013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.148  cargo            139078 139070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.158  cargo-native-tr  139079 139013   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.162  cargo            139082 139079   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.163  rustc            139081 139078   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.174  rustc            139084 139082   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.178  rustc            139085 139078   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.186  rustc            139087 139082   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.194  execsnoop        139092 139070   0 /usr/local/bin/execsnoop -t\n16.194  python3          139092 139070   0 \n16.203  execsnoop        139097 139079   0 /usr/local/bin/execsnoop -t\n16.204  python3          139097 139079   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.509  runc             139113 119243   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 --log-format json --systemd-cgroup kill --all 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d 9\n16.527  runc             139121 119243   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 --log-format json --systemd-cgroup delete 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d\n16.590  cc               139130 138945   0 /tmp/native-trace-137337-1783993046182/shims/cc -Wl,--version-script=/target/debug/deps/rustcv5jtOP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv5jtOP/symbols.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.14.rcgu.o ...\n16.591  cc               139131 139130   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcv5jtOP/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcv5jtOP/symbols.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-c41dc2afe98d9c45.thiserror_impl.6a918bdb32b4379b-cgu.14.rcgu.o ...\n16.593  collect2         139132 139131   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv5jtOP/raw-dylibs ...\n16.595  ld.lld           139133 139132   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcv5jtOP/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.596  rust-lld         139133 139132   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIxe3LC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-c41dc2afe98d9c45.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.625  runc             139150 119322   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c --log-format json --systemd-cgroup kill --all eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced 9\n16.643  runc             139156 119322   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c --log-format json --systemd-cgroup delete eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced\n16.703  containerd-shim  139163 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f08942 delete\n16.706  runc             139170 139163   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929 --log-format json delete --force 9da068dbd0cf67569eca360959cabb12c657fe74230af7fd16393f089425929d\n16.726  rustc            139177 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.59/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=171bc390f5653ae1 ...\n16.742  systemd-sysctl   139181 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2374113 --prefix=/net/ipv4/neigh/veth2374113 --prefix=/net/ipv6/conf/veth2374113 --prefix=/net/ipv6/neigh/veth2374113\n16.753  rustc            139186 137923   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"protobuf\" --check-cfg cfg(docsrs,test) ...\n16.843  containerd-shim  139190 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964c delete\n16.846  runc             139197 139190   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ce --log-format json delete --force eb81089421d0693459ec0dbba639a10ac20e12da2d858cd60f90648964cc9ced\n16.880  systemd-sysctl   139202 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha5668f0 --prefix=/net/ipv4/neigh/vetha5668f0 --prefix=/net/ipv6/conf/vetha5668f0 --prefix=/net/ipv6/neigh/vetha5668f0\n17.184  sh               139203 2147557   0 /bin/sh -c which ps\n17.186  which            139203 2147557   0 /usr/bin/which ps\n17.188  sh               139204 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.189  ps               139204 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.214  sh               139205 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.216  cpuUsage.sh      139205 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.217  sed              139206 139205   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.219  cat              139207 139205   0 /usr/bin/cat /proc/2240539/stat\n17.221  cat              139208 139205   0 /usr/bin/cat /proc/4193716/stat\n17.222  sleep            139209 139205   0 /usr/bin/sleep 1\n17.274  git              139210 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.929  cargo            139375 138585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.941  rustc            139376 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.957  rustc            139382 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.049  cc               139430 139382   0 /tmp/native-trace-138585-1783993050827/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc0UvATj/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1ngq6ad.rcgu.o ...\n18.050  cc               139431 139430   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc0UvATj/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1ngq6ad.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1ngq6ad.rcgu.o ...\n18.053  collect2         139432 139431   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.055  ld.lld           139433 139432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.056  rust-lld         139433 139432   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccv2RunT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.106  build-script-bu  139451 139375   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.107  rustc            139452 139451   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.120  rustc            139455 139375   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=9a2474cc3d7283b6 ...\n18.224  sed              139462 139205   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.226  cat              139463 139205   0 /usr/bin/cat /proc/2240539/stat\n18.228  cat              139465 139205   0 /usr/bin/cat /proc/4193716/stat\n18.272  cargo            139467 139070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n18.285  rustc            139468 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.304  rustc            139475 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.312  cargo            139477 139079   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.313  git              139476 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n18.325  rustc            139481 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.341  rustc            139487 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a1a3bbc558e1e540 ...\n18.388  cc               139535 139475   0 /tmp/native-trace-139070-1783993051779/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustcTmBawo/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1a96nkb.rcgu.o ...\n18.389  cc               139536 139535   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustcTmBawo/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.1a96nkb.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.1a96nkb.rcgu.o ...\n18.393  collect2         139539 139536   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.394  ld.lld           139540 139539   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.396  rust-lld         139540 139539   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXy1f6d.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.429  cc               139599 139487   0 /tmp/native-trace-139079-1783993051796/shims/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc94wMcA/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.0ql1bhj.rcgu.o ...\n18.429  cc               139600 139599   0 /usr/bin/cc -m64 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/rustc94wMcA/symbols.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0c9hy9bvsvrjbbivcer5c90tj.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0e1he10gnv21c196dsn8aqsg1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.0xfn55rlrzlddkk20t5lhvesa.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.16nvow7mu44f6tdn2xu02ych1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1kfwgokx23ro44ollp1qq21vb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.1t65jhkh192ea4kjdg2rn5egn.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2hew67pht7u1x5ycs37k4a4vp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.2ui285xny7eh9yd34xw4eskfv.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.3pxivzxq17hive6p4lir0fhbb.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4263ir824zs751zvidav3ehl0.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.461tfl0b2w00tifylsdd7g52s.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.4ffwikk297oc1fn7ms3plh9l1.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.58bjfmzsjczuinjcjoeu9z771.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5blztooru7vrkijwsxpddtlrw.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5duapsxj26nafsnvao7sxceoi.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5q1o4hl5u785a7og6p8abranp.0ql1bhj.rcgu.o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81.5xbeg470xdfcuzbhfc059j7n6.0ql1bhj.rcgu.o ...\n18.433  collect2         139601 139600   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.434  ld.lld           139602 139601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build_script_build-c0e9b548d5b0da81 ...\n18.435  rust-lld         139602 139601   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqT3LP7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.449  build-script-bu  139620 139467   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.451  rustc            139621 139620   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.463  rustc            139624 139467   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2e81567ac1e8ee66 ...\n18.484  build-script-bu  139632 139477   0 /target/debug/build/maybe-uninit-c0e9b548d5b0da81/build-script-build\n18.486  rustc            139633 139632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n18.499  rustc            139636 139477   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name maybe_uninit --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=75caea18bd00badc ...\n19.112  cross            139643 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n19.113  rustc            139646 139643   0 /home/xmoe/.cargo/bin/rustc --print target-list\n19.118  rustc            139646 139643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n"
    },
    {
      "argv": [
        "/target/debug/build/quote-c09a40bfdaa87378/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133619,
      "build_script_target_dir": "quote-c09a40bfdaa87378",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/quote-c09a40bfdaa87378/build-script-build",
      "pid": 133619,
      "ppid": 133530,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133619,
      "build_script_target_dir": "quote-c09a40bfdaa87378",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133621,
      "ppid": 133619,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build",
      "pid": 133624,
      "ppid": 133530,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133625,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133631,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span_location.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133646,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span_file.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133655,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133683,
      "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build",
      "pid": 133683,
      "ppid": 133530,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133683,
      "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133684,
      "ppid": 133683,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "quote",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "event_id": "bsrun:f98078fec332daf1:1a6a29dd7a1e190e:4757e729dcc8c47e",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/quote-c09a40bfdaa87378/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
      "out_dir": "/target/debug/build/quote-c09a40bfdaa87378/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "success": true,
      "target": null,
      "version": "1.0.46",
      "_owner": {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "proc-macro2",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "event_id": "bsrun:de579e35607e37bb:2fcd632d4d8cac39:4c7913c0d47ce57e",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
      "out_dir": "/target/debug/build/proc-macro2-3d1201f1e2c08588/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "success": true,
      "target": null,
      "version": "1.0.106",
      "_owner": {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "proc-macro2-diagnostics",
      "cwd": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "event_id": "bsrun:b79cb7451ab038ab:e545dc5618aa31f5:3b8f426181e61f09",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
      "out_dir": "/target/debug/build/proc-macro2-diagnostics-a3bc0c613ed5c143/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
      "success": true,
      "target": null,
      "version": "0.10.1",
      "_owner": {
        "crate": "proc-macro2-diagnostics",
        "version": "0.10.1",
        "package_id": "path+file:///tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1#proc-macro2-diagnostics@0.10.1",
        "manifest_dir": "/tmp/crate-build-aarch64-mwu3o60d/src/proc-macro2-diagnostics-0.10.1",
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
      "build_script_root_pid": 133619,
      "build_script_target_dir": "quote-c09a40bfdaa87378",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133621,
      "ppid": 133619,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133625,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133631,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span_location.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133646,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--cfg=procmacro2_build_probe",
        "--edition=2021",
        "--crate-name=proc_macro2",
        "--crate-type=lib",
        "--cap-lints=allow",
        "--emit=dep-info,metadata",
        "--out-dir",
        "/target/aarch64-unknown-linux-gnu/debug/build/proc-macro2-439c5de7a7e8340d/out/probe",
        "src/probe/proc_macro_span_file.rs",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133624,
      "build_script_target_dir": "proc-macro2-3d1201f1e2c08588",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133655,
      "ppid": 133624,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 133683,
      "build_script_target_dir": "proc-macro2-diagnostics-a3bc0c613ed5c143",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 133684,
      "ppid": 133683,
      "root_cargo_pid": 133530,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 669,
    "crate": "proc-macro2-diagnostics",
    "version": "0.10.1",
    "crate_id": "297932",
    "version_id": "843312",
    "downloads": 41712148,
    "cumulative_downloads": 79439883046,
    "cumulative_share_of_global": 0.29700738355003636,
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
