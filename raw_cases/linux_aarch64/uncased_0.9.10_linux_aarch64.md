# `uncased` `0.9.10`

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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
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
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
    "/target/debug/build/uncased-75d093de25ddc81b",
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
      "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-199318-1783993223236596543.map",
  "pid": 199318,
  "ppid": 199300,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-199318-1783993223236596543.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "workspace_root": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
      "name": "uncased",
      "version": "0.9.10",
      "manifest_path": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
      "name": "version_check",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
    }
  ],
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 199318,
  "ppid": 199300,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:318d2b2c496766bb:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
  "pid": 199318,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:f879060efed1b557:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "36764a96349ae351a511355650e100c2e18aedc04880e86eb7d389f1f6f7eea3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:886c997fbc9ac9e3:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "65c374a6586f6c5a27d5ac4a40dc5e7a857a7c789f1fab72938a85237e2c945b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:5ec8e40fff01dd64:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "db74a99fe06b2f0a0a02ea709c5eb4ff6d08ba3d697f9d543c29f4ddc1eeed0c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:bc5054ad3ce22db5:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "9d4eb7f1215cb3ac28004577e5d6defc4dc0cccc9530c19bd57047ce94fbf0de",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:f1dc190f9018778f:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "67c92b1712c62c031f555f02367a1f35ed6363b53be274a2a261731644de0e82",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:113dc4d53a845619:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "ebe93ecd6c1d214ea93f65c4dbb37c3b2bf0227eacfdd73a2d5d57833da3d4e5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "used:cc:9269f9fafd1ef965:2cf6af820df19c66:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
  "pid": 199318,
  "sha256": "d026706d111433c3ec386f86441995a7d2260bf60592a3732e01a10ac45fe1a4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
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
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "context_path": "/tmp/native-trace-197911-1783993218258/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-197911-1783993218258/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 199318,
  "ppid": 199300,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
    "/target/debug/build/uncased-75d093de25ddc81b",
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
      "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-199318-1783993223236596543.map",
  "pid": 199318,
  "ppid": 199300,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-199318-1783993223236596543.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
  "parsed_event_count": 1294,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1296,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "u/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/ticker.pic.o -D _GNU_SOURCE -D _REENTRANT src/ticker.c -o ...\n9.939   riscv64-linux-g  201383 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/rtree.pic.o -o src/rtree.pic.d ...\n9.945   cc1              201384 201383   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/rtree.pic.o -D _GNU_SOURCE -D _REENTRANT src/rtree.c -o ...\n9.987   riscv64-linux-g  201385 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/tsd.pic.o -o src/tsd.pic.d ...\n9.992   cc1              201386 201385   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/tsd.pic.o -D _GNU_SOURCE -D _REENTRANT src/tsd.c -o ...\n10.021  riscv64-linux-g  201387 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_log.pic.o -o src/prof_log.pic.d ...\n10.024  cc1              201388 201387   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/prof_log.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_log.c -o ...\n10.096  riscv64-linux-g  201389 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/tcache.pic.o -o src/tcache.pic.d ...\n10.099  cc1              201390 201389   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/tcache.pic.o -D _GNU_SOURCE -D _REENTRANT src/tcache.c -o ...\n10.251  powerpc64le-lin  201391 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/stats.pic.o -o src/stats.pic.d src/stats.c ...\n10.255  cc1              201392 201391   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/stats.pic.o -D _GNU_SOURCE -D _REENTRANT src/stats.c -o src/stats.pic.d -msecure-plt ...\n10.325  runc             201393 192393   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 --log-format json --systemd-cgroup kill --all c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58 9\n10.350  runc             201399 192393   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 --log-format json --systemd-cgroup delete c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58\n10.364  runc             201405 192621   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b --log-format json --systemd-cgroup kill --all c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7 9\n10.403  powerpc64le-lin  201411 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_data.pic.o -o src/prof_data.pic.d src/prof_data.c ...\n10.406  cc1              201412 201411   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/prof_data.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_data.c -o src/prof_data.pic.d -msecure-plt ...\n10.407  runc             201413 192621   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b --log-format json --systemd-cgroup delete c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7\n10.520  riscv64-linux-g  201419 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/stats.pic.o -o src/stats.pic.d ...\n10.523  cc1              201420 201419   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/stats.pic.o -D _GNU_SOURCE -D _REENTRANT src/stats.c -o ...\n10.529  riscv64-linux-g  201421 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_data.pic.o -o src/prof_data.pic.d ...\n10.531  cc1              201422 201421   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/prof_data.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_data.c -o ...\n10.568  containerd-shim  201424 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 delete\n10.573  runc             201431 201424   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d5 --log-format json delete --force c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58\n10.609  systemd-sysctl   201436 201274   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc90330b --prefix=/net/ipv4/neigh/vethc90330b --prefix=/net/ipv6/conf/vethc90330b --prefix=/net/ipv6/neigh/vethc90330b\n10.635  containerd-shim  201437 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b delete\n10.639  runc             201443 201437   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e --log-format json delete --force c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7\n10.647  rustup           201449 191994   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n10.676  systemd-sysctl   201458 201274   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4f91c72 --prefix=/net/ipv4/neigh/veth4f91c72 --prefix=/net/ipv6/conf/veth4f91c72 --prefix=/net/ipv6/neigh/veth4f91c72\n10.720  rustup           201459 192433   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n11.127  sh               201468 2147557   0 /bin/sh -c which ps\n11.128  which            201468 2147557   0 /usr/bin/which ps\n11.132  sh               201469 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n11.134  ps               201469 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n11.163  sh               201470 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n11.165  cpuUsage.sh      201470 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n11.166  sed              201471 201470   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.169  cat              201472 201470   0 /usr/bin/cat /proc/2240539/stat\n11.171  cat              201473 201470   0 /usr/bin/cat /proc/4193716/stat\n11.173  sleep            201474 201470   0 /usr/bin/sleep 1\n12.175  sed              201475 201470   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.178  cat              201476 201470   0 /usr/bin/cat /proc/2240539/stat\n12.180  cat              201478 201470   0 /usr/bin/cat /proc/4193716/stat\n12.660  cargo            201480 201360   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n12.676  rustc            201481 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.697  rustc            201487 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n13.281  rustc            201510 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n13.360  cc               201533 201510   0 /tmp/native-trace-201360-1783993232080/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcJn6361/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.0cjvh82.rcgu.o ...\n13.362  cc               201534 201533   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcJn6361/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.0cjvh82.rcgu.o ...\n13.365  collect2         201535 201534   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.367  ld.lld           201536 201535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n13.369  rust-lld         201536 201535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.440  build-script-bu  201555 201480   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n13.444  riscv64-linux-g  201556 201555   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_riscv64 -DCFG_TARGET_ENV_gnu -o /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o -c src/arch/riscv64.s ...\n13.446  cc1              201558 201556   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 -D CFG_TARGET_ENV_gnu src/arch/riscv64.s -march=rv64gc -mabi=lp64d -mcmodel=medany -misa-spec=2.2 -march=rv64imafdc ...\n13.453  as               201559 201556   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-5 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o /tmp/ccwWDS0U.s\n13.457  riscv64-linux-g  201560 201555   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o\n13.478  riscv64-linux-g  201562 201555   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a\n13.502  rustc            201565 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=78359f6b25e7e3ee ...\n14.138  cross            201573 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n14.140  rustc            201576 201573   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.146  rustc            201576 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.147  cross            201585 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n14.148  rustc            201587 201585   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.155  rustc            201587 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.162  rustc            201600 201573   0 /home/xmoe/.cargo/bin/rustc -vV\n14.172  rustc            201600 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.172  rustc            201612 201585   0 /home/xmoe/.cargo/bin/rustc -vV\n14.180  rustc            201612 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.185  cargo            201622 201573   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.191  cargo            201622 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.191  cargo            201632 201585   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n14.202  cargo            201632 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n14.206  rustc            201641 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.215  rustc            201642 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.220  rustc            201644 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.227  rustc            201646 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.235  rustc            201650 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.242  rustc            201654 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.255  rustc            201661 201573   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.261  rustc            201661 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.274  docker           201674 201573   0 /usr/bin/docker --help\n14.289  docker           201687 201573   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.305  runc             201697 1599     0 /usr/bin/runc --version\n14.308  docker-init      201703 1599     0 /usr/bin/docker-init --version\n14.311  docker           201705 201573   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.325  runc             201715 1599     0 /usr/bin/runc --version\n14.329  docker-init      201721 1599     0 /usr/bin/docker-init --version\n14.354  rustup           201722 201573   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.361  rustup           201731 201573   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.389  rustup           201740 201573   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.414  rustc            201750 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.415  aarch64-linux-g  201749 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c\n14.417  uname            201751 201573   0 /usr/bin/uname -r\n14.417  cc1              201752 201749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -mlittle-endian ...\n14.440  docker           201754 201573   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.442  rustc            201758 201585   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.450  rustc            201758 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.454  mkdir            201775 183581   0 /usr/bin/mkdir -p lib\n14.456  ar               201776 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n14.458  ar               201777 201776   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n14.465  docker           201781 201585   0 /usr/bin/docker --help\n14.481  docker           201793 201585   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.497  runc             201804 1599     0 /usr/bin/runc --version\n14.502  docker-init      201810 1599     0 /usr/bin/docker-init --version\n14.505  docker           201811 201585   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.510  systemd-sysctl   201819 201812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb607043 --prefix=/net/ipv4/neigh/vethb607043 --prefix=/net/ipv6/conf/vethb607043 --prefix=/net/ipv6/neigh/vethb607043\n14.513  systemd-sysctl   201820 201818   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82113 --prefix=/net/ipv4/neigh/veth3a82113 --prefix=/net/ipv6/conf/veth3a82113 --prefix=/net/ipv6/neigh/veth3a82113\n14.530  runc             201844 1599     0 /usr/bin/runc --version\n14.533  containerd-shim  201859 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e start\n14.537  docker-init      201860 1599     0 /usr/bin/docker-init --version\n14.541  containerd-shim  201866 201859   0 \n14.547  runc             201877 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n14.555  exe              201884 201877   0 /proc/self/exe init\n14.565  rustup           201887 201585   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.574  rustup           201903 201585   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.592  exe              201912 201877   0 /proc/1599/exe -exec-root=/var/run/docker 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e d7da31e8f8e1\n14.602  rustup           201919 201585   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.618  exe              201929 1599     0 /proc/self/exe /var/run/docker/netns/731df16afe4b all false\n14.632  uname            201938 201585   0 /usr/bin/uname -r\n14.652  docker           201943 201585   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.678  runc             201954 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup start 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n14.686  sh               201897 201866   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.688  cargo            201960 201897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n14.698  systemd-sysctl   201961 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdffa2b9 --prefix=/net/ipv4/neigh/vethdffa2b9 --prefix=/net/ipv6/conf/vethdffa2b9 --prefix=/net/ipv6/neigh/vethdffa2b9\n14.698  systemd-sysctl   201962 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth203181a --prefix=/net/ipv4/neigh/veth203181a --prefix=/net/ipv6/conf/veth203181a --prefix=/net/ipv6/neigh/veth203181a\n14.705  cargo-native-tr  201960 201897   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n14.713  cargo            201963 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.728  rustc            201964 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.738  containerd-shim  201966 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de start\n14.742  containerd-shim  201974 201966   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de -address /var/run/docker/containerd/containerd.sock\n14.743  rustc            201970 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.747  runc             201983 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n14.756  exe              201993 201983   0 /proc/self/exe init\n14.762  execsnoop        201996 201960   0 /usr/local/bin/execsnoop -t\n14.764  python3          201996 201960   0 \n14.787  exe              202006 201983   0 /proc/1599/exe -exec-root=/var/run/docker a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de d7da31e8f8e1\n14.815  exe              202014 1599     0 /proc/self/exe /var/run/docker/netns/34b60308b67c all false\n14.866  runc             202025 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup kill --all db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a 9\n14.883  runc             202032 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup start a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n14.887  runc             202038 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup delete db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n14.890  sh               202000 201974   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.892  cargo            202044 202000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n14.909  cargo-native-tr  202044 202000   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n14.914  cargo            202045 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.926  rustc            202046 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.940  rustc            202048 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.960  execsnoop        202052 202044   0 /usr/local/bin/execsnoop -t\n14.961  python3          202052 202044   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.030  runc             202055 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2327736004 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.036  exe              202062 202055   0 /proc/self/exe init\n15.063  curl             202064 202055   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.121  containerd-shim  202071 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 delete\n15.124  runc             202078 202071   0 \n15.147  aarch64-linux-g  202084 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c\n15.148  cc1              202085 202084   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -mlittle-endian ...\n15.158  systemd-sysctl   202086 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda73173 --prefix=/net/ipv4/neigh/vethda73173 --prefix=/net/ipv6/conf/vethda73173 --prefix=/net/ipv6/neigh/vethda73173\n15.184  mkdir            202087 183581   0 /usr/bin/mkdir -p lib\n15.186  ar               202088 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n15.188  ar               202089 202088   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n15.425  make             202090 168808   0 /tmp/native-trace-167169-1783993149691/shims/make install_lib_static install_include -j 16\n15.426  make             202091 202090   0 /usr/bin/make install_lib_static install_include -j 16\n15.448  install          202092 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.448  install          202093 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n15.451  sh               202095 202091   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/aarch64-unknown-linux-gnu/debug/build/tik\n15.451  sh               202094 202091   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/aarch64-unknown-linux-gnu/deb\n15.453  install          202096 202095   0 \n15.453  install          202097 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.484  install          202098 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.519  rustc            202100 168219   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.026  runc             202107 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup kill --all 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be 9\n16.045  runc             202113 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup delete 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n16.126  sh               202119 2147557   0 /bin/sh -c which ps\n16.127  which            202119 2147557   0 /usr/bin/which ps\n16.130  sh               202120 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.132  ps               202120 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.161  sh               202121 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.162  cpuUsage.sh      202121 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.164  sed              202122 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.166  cat              202123 202121   0 /usr/bin/cat /proc/2240539/stat\n16.168  cat              202124 202121   0 /usr/bin/cat /proc/4193716/stat\n16.169  sleep            202125 202121   0 /usr/bin/sleep 1\n16.227  containerd-shim  202126 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 delete\n16.230  runc             202133 202126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7b --log-format json delete --force 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n16.274  systemd-sysctl   202138 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd6275bb --prefix=/net/ipv4/neigh/vethd6275bb --prefix=/net/ipv6/conf/vethd6275bb --prefix=/net/ipv6/neigh/vethd6275bb\n16.342  rustup           202139 193151   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.426  powerpc64le-lin  202148 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c ...\n16.427  cc1              202149 202148   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -msecure-plt ...\n16.458  mkdir            202150 186442   0 /usr/bin/mkdir -p lib\n16.460  ar               202151 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n16.461  ar               202152 202151   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n16.765  runc             202153 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup kill --all 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 9\n16.785  runc             202159 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup delete 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n16.990  containerd-shim  202165 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 delete\n16.993  runc             202171 202165   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d463 --log-format json delete --force 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n17.030  systemd-sysctl   202177 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha86f86b --prefix=/net/ipv4/neigh/vetha86f86b --prefix=/net/ipv6/conf/vetha86f86b --prefix=/net/ipv6/neigh/vetha86f86b\n17.081  cargo            202178 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.096  rustc            202179 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.116  rustc            202185 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n17.171  sed              202189 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.175  cat              202190 202121   0 /usr/bin/cat /proc/2240539/stat\n17.176  cat              202192 202121   0 /usr/bin/cat /proc/4193716/stat\n17.245  cargo            202194 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.263  rustc            202195 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.286  rustc            202203 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n17.286  rustc            202202 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.447  powerpc64le-lin  202217 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c ...\n17.449  cc1              202218 202217   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -msecure-plt ...\n17.481  mkdir            202224 186442   0 /usr/bin/mkdir -p lib\n17.484  ar               202225 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n17.485  ar               202226 202225   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n17.503  cc               202229 202202   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.505  cc               202230 202229   0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.508  collect2         202232 202230   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.510  ld.lld           202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707 ...\n17.512  rust-lld         202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.575  build-script-bu  202259 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n17.576  build-script-bu  202260 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n17.577  rustc            202261 202259   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.579  rustc            202263 202260   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.592  rustc            202266 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.596  rustc            202270 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.639  rustc            202279 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n17.705  cc               202302 202279   0 /tmp/native-trace-201960-1783993237281/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n17.706  cc               202303 202302   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n17.709  collect2         202304 202303   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.711  ld.lld           202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n17.713  rust-lld         202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.736  make             202328 170525   0 /tmp/native-trace-167505-1783993150345/shims/make install_lib_static install_include -j 16\n17.737  make             202329 202328   0 /usr/bin/make install_lib_static install_include -j 16\n17.761  install          202334 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.762  install          202335 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n17.763  sh               202336 202329   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/powerpc64le-unknown-linux-gnu\n17.764  sh               202337 202329   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/powerpc64le-unknown-linux-gnu/debug/build\n17.765  install          202338 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.765  install          202339 202337   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n17.783  rustc            202341 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n17.784  build-script-bu  202343 202178   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n17.787  powerpc64le-lin  202344 202343   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_powerpc64 -DCFG_TARGET_ENV_gnu -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o -c src/arch/powerpc64_openpower.s\n17.789  cc1              202346 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -imultiarch powerpc64le-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_powerpc64 -D CFG_TARGET_ENV_gnu src/arch/powerpc64_openpower.s -msecure-plt -m64 -mcpu=power8 -Wall -Wextra -ffunction-sections -fdata-sections ...\n17.794  as               202351 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o /tmp/ccKOqcNw.s\n17.794  install          202350 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.800  powerpc64le-lin  202352 202343   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o\n17.803  powerpc64le-lin  202354 202343   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a\n17.809  rustc            202357 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e8967af7065dad73 ...\n17.829  rustc            202362 168713   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/uncased-75d093de25ddc81b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199357,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
  "pid": 199357,
  "ppid": 199207,
  "root_cargo_pid": 199207,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out"
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199357,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199358,
  "ppid": 199357,
  "root_cargo_pid": 199207,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199357,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199381,
  "ppid": 199357,
  "root_cargo_pid": 199207,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_build_script_out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "uncased",
  "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "event_id": "bsrun:4b075a0af5ea0470:f506a86cb9642b5d:2640f7a39d4cfbf2",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
  "out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
  "success": true,
  "target": null,
  "version": "0.9.10",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
    "source": "cwd_prefix"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199357,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199358,
  "ppid": 199357,
  "root_cargo_pid": 199207,
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
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199357,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199381,
  "ppid": 199357,
  "root_cargo_pid": 199207,
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
  "time": "2026-07-14T01:40:41.029495+00:00",
  "crate": "uncased",
  "version": "0.9.10",
  "architecture": "aarch64",
  "duration_seconds": 27.938576861750335,
  "trace_record_count": 19,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "version_check",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml"
      },
      {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "manifest_path": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "uncased",
        "version": "0.9.10",
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
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "workspace_root": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
          "name": "uncased",
          "version": "0.9.10",
          "manifest_path": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.5",
          "name": "version_check",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.5"
        }
      ],
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 199318,
      "ppid": 199300,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:318d2b2c496766bb:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
      "pid": 199318,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:f879060efed1b557:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "36764a96349ae351a511355650e100c2e18aedc04880e86eb7d389f1f6f7eea3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:886c997fbc9ac9e3:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "65c374a6586f6c5a27d5ac4a40dc5e7a857a7c789f1fab72938a85237e2c945b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:5ec8e40fff01dd64:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "db74a99fe06b2f0a0a02ea709c5eb4ff6d08ba3d697f9d543c29f4ddc1eeed0c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:bc5054ad3ce22db5:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "9d4eb7f1215cb3ac28004577e5d6defc4dc0cccc9530c19bd57047ce94fbf0de",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:f1dc190f9018778f:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "67c92b1712c62c031f555f02367a1f35ed6363b53be274a2a261731644de0e82",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:113dc4d53a845619:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "ebe93ecd6c1d214ea93f65c4dbb37c3b2bf0227eacfdd73a2d5d57833da3d4e5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "used:cc:9269f9fafd1ef965:2cf6af820df19c66:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
      "pid": 199318,
      "sha256": "d026706d111433c3ec386f86441995a7d2260bf60592a3732e01a10ac45fe1a4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
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
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "context_path": "/tmp/native-trace-197911-1783993218258/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-197911-1783993218258/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 199318,
      "ppid": 199300,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
        "/target/debug/build/uncased-75d093de25ddc81b",
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
          "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcTRIyGZ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.173xs29.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.173xs29.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-199318-1783993223236596543.map",
      "pid": 199318,
      "ppid": 199300,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-199318-1783993223236596543.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
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
      "parsed_event_count": 1294,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1296,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "u/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/ticker.pic.o -D _GNU_SOURCE -D _REENTRANT src/ticker.c -o ...\n9.939   riscv64-linux-g  201383 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/rtree.pic.o -o src/rtree.pic.d ...\n9.945   cc1              201384 201383   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/rtree.pic.o -D _GNU_SOURCE -D _REENTRANT src/rtree.c -o ...\n9.987   riscv64-linux-g  201385 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/tsd.pic.o -o src/tsd.pic.d ...\n9.992   cc1              201386 201385   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/tsd.pic.o -D _GNU_SOURCE -D _REENTRANT src/tsd.c -o ...\n10.021  riscv64-linux-g  201387 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_log.pic.o -o src/prof_log.pic.d ...\n10.024  cc1              201388 201387   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/prof_log.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_log.c -o ...\n10.096  riscv64-linux-g  201389 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/tcache.pic.o -o src/tcache.pic.d ...\n10.099  cc1              201390 201389   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/tcache.pic.o -D _GNU_SOURCE -D _REENTRANT src/tcache.c -o ...\n10.251  powerpc64le-lin  201391 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/stats.pic.o -o src/stats.pic.d src/stats.c ...\n10.255  cc1              201392 201391   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/stats.pic.o -D _GNU_SOURCE -D _REENTRANT src/stats.c -o src/stats.pic.d -msecure-plt ...\n10.325  runc             201393 192393   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 --log-format json --systemd-cgroup kill --all c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58 9\n10.350  runc             201399 192393   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 --log-format json --systemd-cgroup delete c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58\n10.364  runc             201405 192621   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b --log-format json --systemd-cgroup kill --all c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7 9\n10.403  powerpc64le-lin  201411 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_data.pic.o -o src/prof_data.pic.d src/prof_data.c ...\n10.406  cc1              201412 201411   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/prof_data.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_data.c -o src/prof_data.pic.d -msecure-plt ...\n10.407  runc             201413 192621   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b --log-format json --systemd-cgroup delete c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7\n10.520  riscv64-linux-g  201419 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/stats.pic.o -o src/stats.pic.d ...\n10.523  cc1              201420 201419   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/stats.pic.o -D _GNU_SOURCE -D _REENTRANT src/stats.c -o ...\n10.529  riscv64-linux-g  201421 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/prof_data.pic.o -o src/prof_data.pic.d ...\n10.531  cc1              201422 201421   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/prof_data.pic.o -D _GNU_SOURCE -D _REENTRANT src/prof_data.c -o ...\n10.568  containerd-shim  201424 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e873 delete\n10.573  runc             201431 201424   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d5 --log-format json delete --force c9dc66a9cb274bcbb9d840fbcf3f194834b93b2148ba9d15acd6a55e87314d58\n10.609  systemd-sysctl   201436 201274   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc90330b --prefix=/net/ipv4/neigh/vethc90330b --prefix=/net/ipv6/conf/vethc90330b --prefix=/net/ipv6/neigh/vethc90330b\n10.635  containerd-shim  201437 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b delete\n10.639  runc             201443 201437   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e --log-format json delete --force c5e0e3f0611402a86d11b819884bed750ef43a46d471561d711e151e30b6b8e7\n10.647  rustup           201449 191994   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n10.676  systemd-sysctl   201458 201274   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth4f91c72 --prefix=/net/ipv4/neigh/veth4f91c72 --prefix=/net/ipv6/conf/veth4f91c72 --prefix=/net/ipv6/neigh/veth4f91c72\n10.720  rustup           201459 192433   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n11.127  sh               201468 2147557   0 /bin/sh -c which ps\n11.128  which            201468 2147557   0 /usr/bin/which ps\n11.132  sh               201469 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n11.134  ps               201469 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n11.163  sh               201470 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n11.165  cpuUsage.sh      201470 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n11.166  sed              201471 201470   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n11.169  cat              201472 201470   0 /usr/bin/cat /proc/2240539/stat\n11.171  cat              201473 201470   0 /usr/bin/cat /proc/4193716/stat\n11.173  sleep            201474 201470   0 /usr/bin/sleep 1\n12.175  sed              201475 201470   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.178  cat              201476 201470   0 /usr/bin/cat /proc/2240539/stat\n12.180  cat              201478 201470   0 /usr/bin/cat /proc/4193716/stat\n12.660  cargo            201480 201360   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n12.676  rustc            201481 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.697  rustc            201487 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n13.281  rustc            201510 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n13.360  cc               201533 201510   0 /tmp/native-trace-201360-1783993232080/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcJn6361/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.0cjvh82.rcgu.o ...\n13.362  cc               201534 201533   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcJn6361/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.0cjvh82.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.0cjvh82.rcgu.o ...\n13.365  collect2         201535 201534   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.367  ld.lld           201536 201535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n13.369  rust-lld         201536 201535   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccdZURz6.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.440  build-script-bu  201555 201480   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n13.444  riscv64-linux-g  201556 201555   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_riscv64 -DCFG_TARGET_ENV_gnu -o /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o -c src/arch/riscv64.s ...\n13.446  cc1              201558 201556   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -lang-asm -quiet -imultilib . -imultiarch riscv64-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_riscv64 -D CFG_TARGET_ENV_gnu src/arch/riscv64.s -march=rv64gc -mabi=lp64d -mcmodel=medany -misa-spec=2.2 -march=rv64imafdc ...\n13.453  as               201559 201556   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --gdwarf-5 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o /tmp/ccwWDS0U.s\n13.457  riscv64-linux-g  201560 201555   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/src/arch/riscv64.o\n13.478  riscv64-linux-g  201562 201555   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/psm-7d57464142dcb914/out/libpsm_s.a\n13.502  rustc            201565 201480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=78359f6b25e7e3ee ...\n14.138  cross            201573 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n14.140  rustc            201576 201573   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.146  rustc            201576 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.147  cross            201585 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n14.148  rustc            201587 201585   0 /home/xmoe/.cargo/bin/rustc --print target-list\n14.155  rustc            201587 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n14.162  rustc            201600 201573   0 /home/xmoe/.cargo/bin/rustc -vV\n14.172  rustc            201600 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.172  rustc            201612 201585   0 /home/xmoe/.cargo/bin/rustc -vV\n14.180  rustc            201612 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.185  cargo            201622 201573   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.191  cargo            201622 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n14.191  cargo            201632 201585   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n14.202  cargo            201632 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n14.206  rustc            201641 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.215  rustc            201642 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.220  rustc            201644 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.227  rustc            201646 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.235  rustc            201650 201622   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.242  rustc            201654 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n14.255  rustc            201661 201573   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.261  rustc            201661 201573   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.274  docker           201674 201573   0 /usr/bin/docker --help\n14.289  docker           201687 201573   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.305  runc             201697 1599     0 /usr/bin/runc --version\n14.308  docker-init      201703 1599     0 /usr/bin/docker-init --version\n14.311  docker           201705 201573   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.325  runc             201715 1599     0 /usr/bin/runc --version\n14.329  docker-init      201721 1599     0 /usr/bin/docker-init --version\n14.354  rustup           201722 201573   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.361  rustup           201731 201573   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.389  rustup           201740 201573   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.414  rustc            201750 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.415  aarch64-linux-g  201749 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c\n14.417  uname            201751 201573   0 /usr/bin/uname -r\n14.417  cc1              201752 201749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -mlittle-endian ...\n14.440  docker           201754 201573   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.442  rustc            201758 201585   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n14.450  rustc            201758 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n14.454  mkdir            201775 183581   0 /usr/bin/mkdir -p lib\n14.456  ar               201776 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n14.458  ar               201777 201776   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n14.465  docker           201781 201585   0 /usr/bin/docker --help\n14.481  docker           201793 201585   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n14.497  runc             201804 1599     0 /usr/bin/runc --version\n14.502  docker-init      201810 1599     0 /usr/bin/docker-init --version\n14.505  docker           201811 201585   0 /usr/bin/docker info -f {{.SecurityOptions}}\n14.510  systemd-sysctl   201819 201812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb607043 --prefix=/net/ipv4/neigh/vethb607043 --prefix=/net/ipv6/conf/vethb607043 --prefix=/net/ipv6/neigh/vethb607043\n14.513  systemd-sysctl   201820 201818   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82113 --prefix=/net/ipv4/neigh/veth3a82113 --prefix=/net/ipv6/conf/veth3a82113 --prefix=/net/ipv6/neigh/veth3a82113\n14.530  runc             201844 1599     0 /usr/bin/runc --version\n14.533  containerd-shim  201859 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e start\n14.537  docker-init      201860 1599     0 /usr/bin/docker-init --version\n14.541  containerd-shim  201866 201859   0 \n14.547  runc             201877 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n14.555  exe              201884 201877   0 /proc/self/exe init\n14.565  rustup           201887 201585   0 /home/xmoe/.cargo/bin/rustup toolchain list\n14.574  rustup           201903 201585   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n14.592  exe              201912 201877   0 /proc/1599/exe -exec-root=/var/run/docker 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e d7da31e8f8e1\n14.602  rustup           201919 201585   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n14.618  exe              201929 1599     0 /proc/self/exe /var/run/docker/netns/731df16afe4b all false\n14.632  uname            201938 201585   0 /usr/bin/uname -r\n14.652  docker           201943 201585   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n14.678  runc             201954 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup start 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n14.686  sh               201897 201866   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.688  cargo            201960 201897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n14.698  systemd-sysctl   201961 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdffa2b9 --prefix=/net/ipv4/neigh/vethdffa2b9 --prefix=/net/ipv6/conf/vethdffa2b9 --prefix=/net/ipv6/neigh/vethdffa2b9\n14.698  systemd-sysctl   201962 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth203181a --prefix=/net/ipv4/neigh/veth203181a --prefix=/net/ipv6/conf/veth203181a --prefix=/net/ipv6/neigh/veth203181a\n14.705  cargo-native-tr  201960 201897   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n14.713  cargo            201963 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.728  rustc            201964 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.738  containerd-shim  201966 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de start\n14.742  containerd-shim  201974 201966   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de -address /var/run/docker/containerd/containerd.sock\n14.743  rustc            201970 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.747  runc             201983 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n14.756  exe              201993 201983   0 /proc/self/exe init\n14.762  execsnoop        201996 201960   0 /usr/local/bin/execsnoop -t\n14.764  python3          201996 201960   0 \n14.787  exe              202006 201983   0 /proc/1599/exe -exec-root=/var/run/docker a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de d7da31e8f8e1\n14.815  exe              202014 1599     0 /proc/self/exe /var/run/docker/netns/34b60308b67c all false\n14.866  runc             202025 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup kill --all db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a 9\n14.883  runc             202032 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup start a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n14.887  runc             202038 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup delete db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n14.890  sh               202000 201974   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n14.892  cargo            202044 202000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n14.909  cargo-native-tr  202044 202000   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n14.914  cargo            202045 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n14.926  rustc            202046 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.940  rustc            202048 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.960  execsnoop        202052 202044   0 /usr/local/bin/execsnoop -t\n14.961  python3          202052 202044   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n15.030  runc             202055 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2327736004 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n15.036  exe              202062 202055   0 /proc/self/exe init\n15.063  curl             202064 202055   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.121  containerd-shim  202071 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 delete\n15.124  runc             202078 202071   0 \n15.147  aarch64-linux-g  202084 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c\n15.148  cc1              202085 202084   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -mlittle-endian ...\n15.158  systemd-sysctl   202086 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda73173 --prefix=/net/ipv4/neigh/vethda73173 --prefix=/net/ipv6/conf/vethda73173 --prefix=/net/ipv6/neigh/vethda73173\n15.184  mkdir            202087 183581   0 /usr/bin/mkdir -p lib\n15.186  ar               202088 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n15.188  ar               202089 202088   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n15.425  make             202090 168808   0 /tmp/native-trace-167169-1783993149691/shims/make install_lib_static install_include -j 16\n15.426  make             202091 202090   0 /usr/bin/make install_lib_static install_include -j 16\n15.448  install          202092 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.448  install          202093 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n15.451  sh               202095 202091   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/aarch64-unknown-linux-gnu/debug/build/tik\n15.451  sh               202094 202091   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/aarch64-unknown-linux-gnu/deb\n15.453  install          202096 202095   0 \n15.453  install          202097 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.484  install          202098 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n15.519  rustc            202100 168219   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.026  runc             202107 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup kill --all 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be 9\n16.045  runc             202113 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup delete 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n16.126  sh               202119 2147557   0 /bin/sh -c which ps\n16.127  which            202119 2147557   0 /usr/bin/which ps\n16.130  sh               202120 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.132  ps               202120 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.161  sh               202121 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.162  cpuUsage.sh      202121 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.164  sed              202122 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.166  cat              202123 202121   0 /usr/bin/cat /proc/2240539/stat\n16.168  cat              202124 202121   0 /usr/bin/cat /proc/4193716/stat\n16.169  sleep            202125 202121   0 /usr/bin/sleep 1\n16.227  containerd-shim  202126 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 delete\n16.230  runc             202133 202126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7b --log-format json delete --force 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n16.274  systemd-sysctl   202138 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd6275bb --prefix=/net/ipv4/neigh/vethd6275bb --prefix=/net/ipv6/conf/vethd6275bb --prefix=/net/ipv6/neigh/vethd6275bb\n16.342  rustup           202139 193151   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.426  powerpc64le-lin  202148 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c ...\n16.427  cc1              202149 202148   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -msecure-plt ...\n16.458  mkdir            202150 186442   0 /usr/bin/mkdir -p lib\n16.460  ar               202151 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n16.461  ar               202152 202151   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n16.765  runc             202153 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup kill --all 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 9\n16.785  runc             202159 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup delete 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n16.990  containerd-shim  202165 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 delete\n16.993  runc             202171 202165   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d463 --log-format json delete --force 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n17.030  systemd-sysctl   202177 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha86f86b --prefix=/net/ipv4/neigh/vetha86f86b --prefix=/net/ipv6/conf/vetha86f86b --prefix=/net/ipv6/neigh/vetha86f86b\n17.081  cargo            202178 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n17.096  rustc            202179 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.116  rustc            202185 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n17.171  sed              202189 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.175  cat              202190 202121   0 /usr/bin/cat /proc/2240539/stat\n17.176  cat              202192 202121   0 /usr/bin/cat /proc/4193716/stat\n17.245  cargo            202194 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n17.263  rustc            202195 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.286  rustc            202203 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n17.286  rustc            202202 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.447  powerpc64le-lin  202217 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c ...\n17.449  cc1              202218 202217   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -msecure-plt ...\n17.481  mkdir            202224 186442   0 /usr/bin/mkdir -p lib\n17.484  ar               202225 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n17.485  ar               202226 202225   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n17.503  cc               202229 202202   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.505  cc               202230 202229   0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n17.508  collect2         202232 202230   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.510  ld.lld           202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707 ...\n17.512  rust-lld         202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.575  build-script-bu  202259 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n17.576  build-script-bu  202260 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n17.577  rustc            202261 202259   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.579  rustc            202263 202260   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n17.592  rustc            202266 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.596  rustc            202270 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n17.639  rustc            202279 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n17.705  cc               202302 202279   0 /tmp/native-trace-201960-1783993237281/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n17.706  cc               202303 202302   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n17.709  collect2         202304 202303   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.711  ld.lld           202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n17.713  rust-lld         202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.736  make             202328 170525   0 /tmp/native-trace-167505-1783993150345/shims/make install_lib_static install_include -j 16\n17.737  make             202329 202328   0 /usr/bin/make install_lib_static install_include -j 16\n17.761  install          202334 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.762  install          202335 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n17.763  sh               202336 202329   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/powerpc64le-unknown-linux-gnu\n17.764  sh               202337 202329   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/powerpc64le-unknown-linux-gnu/debug/build\n17.765  install          202338 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.765  install          202339 202337   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n17.783  rustc            202341 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n17.784  build-script-bu  202343 202178   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n17.787  powerpc64le-lin  202344 202343   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_powerpc64 -DCFG_TARGET_ENV_gnu -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o -c src/arch/powerpc64_openpower.s\n17.789  cc1              202346 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -imultiarch powerpc64le-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_powerpc64 -D CFG_TARGET_ENV_gnu src/arch/powerpc64_openpower.s -msecure-plt -m64 -mcpu=power8 -Wall -Wextra -ffunction-sections -fdata-sections ...\n17.794  as               202351 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o /tmp/ccKOqcNw.s\n17.794  install          202350 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n17.800  powerpc64le-lin  202352 202343   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o\n17.803  powerpc64le-lin  202354 202343   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a\n17.809  rustc            202357 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e8967af7065dad73 ...\n17.829  rustc            202362 168713   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n"
    },
    {
      "argv": [
        "/target/debug/build/uncased-75d093de25ddc81b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199357,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
      "pid": 199357,
      "ppid": 199207,
      "root_cargo_pid": 199207,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199357,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199358,
      "ppid": 199357,
      "root_cargo_pid": 199207,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199357,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199381,
      "ppid": 199357,
      "root_cargo_pid": 199207,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "uncased",
      "cwd": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "event_id": "bsrun:4b075a0af5ea0470:f506a86cb9642b5d:2640f7a39d4cfbf2",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
      "out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
      "success": true,
      "target": null,
      "version": "0.9.10",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-aarch64-kvxh1tb9/src/uncased-0.9.10",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199357,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199358,
      "ppid": 199357,
      "root_cargo_pid": 199207,
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
      "build_script_root_pid": 199357,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199381,
      "ppid": 199357,
      "root_cargo_pid": 199207,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 910,
    "crate": "uncased",
    "version": "0.9.10",
    "crate_id": "285395",
    "version_id": "1023293",
    "downloads": 25638666,
    "cumulative_downloads": 87382606579,
    "cumulative_share_of_global": 0.32670339321600744,
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
