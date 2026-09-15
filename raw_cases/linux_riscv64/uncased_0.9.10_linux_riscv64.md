# `uncased` `0.9.10`

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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
    "/target/debug/build/uncased-75d093de25ddc81b",
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
      "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-199606-1783993224406136303.map",
  "pid": 199606,
  "ppid": 199591,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-199606-1783993224406136303.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "workspace_root": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
      "name": "uncased",
      "version": "0.9.10",
      "manifest_path": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10"
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
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 199606,
  "ppid": 199591,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:922d4a293d4f300b:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
  "pid": 199606,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:2b1248427a077d4e:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "fc98b494b56d9bd2b60f6d163fa0fe4662dd351e251e6eb4ddcacd4b96d639aa",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:ee4b1e4df54121e5:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "98c4bc6ceaa1e8a30b838e0cb46e62e6b879081e1851b743a0a4a6d7eeba2b83",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:0ae75b1f5c389619:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "b7a958dda6fb43a2f3acbf4d1fbe387f10fc0ba1f989729fd538d8cfb28e9202",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:111dbe257e8bc987:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "7b38543495a8a3571a12427dae67170823f0c71552f85b876f59dbb43c59e21d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:496b31fde1fae5ba:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "8c290bf5de753dd4f2a147bc66b17faf3acdfd203d47bedb3ba4ac1e7f4752f5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:3d65315e1a0b8567:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "57b3f8c46c049f7418f98d34e31defcda914cde23aecb4fb285645478ab7ae75",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "used:cc:582b699f3345e1bd:a51f5184e8e9be07:d9e089d500bf06f9",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
  "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
  "pid": 199606,
  "sha256": "d026706d111433c3ec386f86441995a7d2260bf60592a3732e01a10ac45fe1a4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "cargo_pkg_name": "uncased",
  "cargo_pkg_version": "0.9.10",
  "context_path": "/tmp/native-trace-198253-1783993219093/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-198253-1783993219093/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 199606,
  "ppid": 199591,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
    "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
    "/target/debug/build/uncased-75d093de25ddc81b",
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
      "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/uncased-75d093de25ddc81b",
      "kind": "object",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-199606-1783993224406136303.map",
  "pid": 199606,
  "ppid": 199591,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-199606-1783993224406136303.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
  "parsed_event_count": 1234,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1236,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " /usr/bin/docker-init --version\n13.206  rustup           201722 201573   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.213  rustup           201731 201573   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.242  rustup           201740 201573   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.266  rustc            201750 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.268  aarch64-linux-g  201749 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c\n13.268  uname            201751 201573   0 /usr/bin/uname -r\n13.269  cc1              201752 201749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -mlittle-endian ...\n13.291  docker           201754 201573   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.294  rustc            201758 201585   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.301  rustc            201758 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.305  mkdir            201775 183581   0 /usr/bin/mkdir -p lib\n13.308  ar               201776 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n13.311  ar               201777 201776   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n13.317  docker           201781 201585   0 /usr/bin/docker --help\n13.333  docker           201793 201585   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.349  runc             201804 1599     0 /usr/bin/runc --version\n13.354  docker-init      201810 1599     0 /usr/bin/docker-init --version\n13.359  docker           201811 201585   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.362  systemd-sysctl   201819 201812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb607043 --prefix=/net/ipv4/neigh/vethb607043 --prefix=/net/ipv6/conf/vethb607043 --prefix=/net/ipv6/neigh/vethb607043\n13.367  systemd-sysctl   201820 201818   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82113 --prefix=/net/ipv4/neigh/veth3a82113 --prefix=/net/ipv6/conf/veth3a82113 --prefix=/net/ipv6/neigh/veth3a82113\n13.379  runc             201844 1599     0 /usr/bin/runc --version\n13.390  docker-init      201860 1599     0 /usr/bin/docker-init --version\n13.390  containerd-shim  201859 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e start\n13.394  containerd-shim  201866 201859   0 \n13.398  runc             201877 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n13.406  exe              201884 201877   0 /proc/self/exe init\n13.417  rustup           201887 201585   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.425  rustup           201903 201585   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.444  exe              201912 201877   0 /proc/1599/exe -exec-root=/var/run/docker 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e d7da31e8f8e1\n13.454  rustup           201919 201585   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.470  exe              201929 1599     0 /proc/self/exe /var/run/docker/netns/731df16afe4b all false\n13.483  uname            201938 201585   0 /usr/bin/uname -r\n13.504  docker           201943 201585   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.530  runc             201954 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup start 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n13.538  sh               201897 201866   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.540  cargo            201960 201897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.550  systemd-sysctl   201962 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth203181a --prefix=/net/ipv4/neigh/veth203181a --prefix=/net/ipv6/conf/veth203181a --prefix=/net/ipv6/neigh/veth203181a\n13.550  systemd-sysctl   201961 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdffa2b9 --prefix=/net/ipv4/neigh/vethdffa2b9 --prefix=/net/ipv6/conf/vethdffa2b9 --prefix=/net/ipv6/neigh/vethdffa2b9\n13.556  cargo-native-tr  201960 201897   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.564  cargo            201963 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.579  rustc            201964 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.589  containerd-shim  201966 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de start\n13.593  containerd-shim  201974 201966   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de -address /var/run/docker/containerd/containerd.sock\n13.594  rustc            201970 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.598  runc             201983 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n13.607  exe              201993 201983   0 /proc/self/exe init\n13.614  execsnoop        201996 201960   0 /usr/local/bin/execsnoop -t\n13.615  python3          201996 201960   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.638  exe              202006 201983   0 /proc/1599/exe -exec-root=/var/run/docker a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de d7da31e8f8e1\n13.668  exe              202014 1599     0 /proc/self/exe /var/run/docker/netns/34b60308b67c all false\n13.717  runc             202025 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup kill --all db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a 9\n13.735  runc             202032 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup start a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n13.738  runc             202038 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup delete db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n13.742  sh               202000 201974   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.744  cargo            202044 202000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.761  cargo-native-tr  202044 202000   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.765  cargo            202045 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.777  rustc            202046 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.791  rustc            202048 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.811  execsnoop        202052 202044   0 /usr/local/bin/execsnoop -t\n13.813  python3          202052 202044   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.881  runc             202055 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2327736004 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n13.888  exe              202062 202055   0 /proc/self/exe init\n13.913  curl             202064 202055   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n13.973  containerd-shim  202071 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 delete\n13.977  runc             202078 202071   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529 --log-format json delete --force db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n13.998  aarch64-linux-g  202084 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c\n14.000  cc1              202085 202084   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -mlittle-endian ...\n14.010  systemd-sysctl   202086 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda73173 --prefix=/net/ipv4/neigh/vethda73173 --prefix=/net/ipv6/conf/vethda73173 --prefix=/net/ipv6/neigh/vethda73173\n14.036  mkdir            202087 183581   0 /usr/bin/mkdir -p lib\n14.038  ar               202088 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n14.040  ar               202089 202088   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n14.277  make             202090 168808   0 /tmp/native-trace-167169-1783993149691/shims/make install_lib_static install_include -j 16\n14.278  make             202091 202090   0 /usr/bin/make install_lib_static install_include -j 16\n14.301  install          202092 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.301  install          202093 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n14.302  sh               202095 202091   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/aarch64-unknown-linux-gnu/debug/build/tik\n14.302  sh               202094 202091   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/aarch64-unknown-linux-gnu/deb\n14.304  install          202096 202095   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n14.304  install          202097 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.336  install          202098 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.370  rustc            202100 168219   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n14.878  runc             202107 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup kill --all 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be 9\n14.897  runc             202113 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup delete 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n14.978  sh               202119 2147557   0 /bin/sh -c which ps\n14.979  which            202119 2147557   0 /usr/bin/which ps\n14.982  sh               202120 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.984  ps               202120 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n15.012  sh               202121 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n15.014  cpuUsage.sh      202121 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n15.015  sed              202122 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.018  cat              202123 202121   0 /usr/bin/cat /proc/2240539/stat\n15.020  cat              202124 202121   0 /usr/bin/cat /proc/4193716/stat\n15.021  sleep            202125 202121   0 /usr/bin/sleep 1\n15.079  containerd-shim  202126 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 delete\n15.082  runc             202133 202126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7b --log-format json delete --force 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n15.126  systemd-sysctl   202138 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd6275bb --prefix=/net/ipv4/neigh/vethd6275bb --prefix=/net/ipv6/conf/vethd6275bb --prefix=/net/ipv6/neigh/vethd6275bb\n15.194  rustup           202139 193151   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.277  powerpc64le-lin  202148 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c ...\n15.279  cc1              202149 202148   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -msecure-plt ...\n15.310  mkdir            202150 186442   0 /usr/bin/mkdir -p lib\n15.311  ar               202151 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n15.313  ar               202152 202151   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n15.617  runc             202153 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup kill --all 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 9\n15.636  runc             202159 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup delete 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n15.842  containerd-shim  202165 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 delete\n15.845  runc             202171 202165   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d463 --log-format json delete --force 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n15.882  systemd-sysctl   202177 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha86f86b --prefix=/net/ipv4/neigh/vetha86f86b --prefix=/net/ipv6/conf/vetha86f86b --prefix=/net/ipv6/neigh/vetha86f86b\n15.933  cargo            202178 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.948  rustc            202179 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.968  rustc            202185 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n16.023  sed              202189 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.026  cat              202190 202121   0 /usr/bin/cat /proc/2240539/stat\n16.028  cat              202192 202121   0 /usr/bin/cat /proc/4193716/stat\n16.096  cargo            202194 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n16.115  rustc            202195 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.137  rustc            202202 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.137  rustc            202203 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n16.298  powerpc64le-lin  202217 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c ...\n16.300  cc1              202218 202217   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -msecure-plt ...\n16.333  mkdir            202224 186442   0 /usr/bin/mkdir -p lib\n16.335  ar               202225 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n16.336  ar               202226 202225   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n16.355  cc               202229 202202   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.357  cc               202230 202229   0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.361  collect2         202232 202230   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.362  ld.lld           202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707 ...\n16.364  rust-lld         202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.426  build-script-bu  202259 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n16.427  build-script-bu  202260 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n16.429  rustc            202261 202259   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.430  rustc            202263 202260   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.444  rustc            202266 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.448  rustc            202270 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.491  rustc            202279 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n16.556  cc               202302 202279   0 /tmp/native-trace-201960-1783993237281/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n16.558  cc               202303 202302   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n16.561  collect2         202304 202303   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.563  ld.lld           202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n16.564  rust-lld         202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.588  make             202328 170525   0 /tmp/native-trace-167505-1783993150345/shims/make install_lib_static install_include -j 16\n16.589  make             202329 202328   0 /usr/bin/make install_lib_static install_include -j 16\n16.612  install          202334 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.614  install          202335 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n16.615  sh               202336 202329   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/powerpc64le-unknown-linux-gnu\n16.617  install          202338 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.617  sh               202337 202329   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/powerpc64le-unknown-linux-gnu/debug/build\n16.617  install          202339 202337   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n16.634  rustc            202341 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n16.635  build-script-bu  202343 202178   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n16.639  powerpc64le-lin  202344 202343   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_powerpc64 -DCFG_TARGET_ENV_gnu -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o -c src/arch/powerpc64_openpower.s\n16.640  cc1              202346 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -imultiarch powerpc64le-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_powerpc64 -D CFG_TARGET_ENV_gnu src/arch/powerpc64_openpower.s -msecure-plt -m64 -mcpu=power8 -Wall -Wextra -ffunction-sections -fdata-sections ...\n16.645  as               202351 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o /tmp/ccKOqcNw.s\n16.645  install          202350 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.651  powerpc64le-lin  202352 202343   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o\n16.654  powerpc64le-lin  202354 202343   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a\n16.661  rustc            202357 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e8967af7065dad73 ...\n16.680  rustc            202362 168713   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.997  runc             202478 197549   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef --log-format json --systemd-cgroup kill --all 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af 9\n17.015  runc             202499 197549   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef --log-format json --systemd-cgroup delete 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af\n17.025  cc               202505 202341   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/rustcWNvPV3/symbols.o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.03ezmiww155e2y9bhx16j02r0.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.073wgqeycbd8pfgx1rrw9hiuv.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.07hyvz4debz23bkngurc123tr.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0ainpf94ghwn565eyo7uia7qy.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0mgnjr8xhrtx4gef9w9sbeywf.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0s11x300aj3936agrc9uu9v08.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.16tnxtpx0n36ebbg7b0hf0an4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.17qykxaloia7j4hm82wwrrcal.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1bjttpdft90gojgwjjkckup47.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1c7y9mivcuftk2x2jgkfzm1bd.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1tdx60jvwm98pgfmpdnu8dnfm.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1utow171ind4l0k0jnol7pxnx.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1w2ys22pc5470llgaz9ry9op5.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1yy585xd9ffm3wnvdou2qv7yc.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.25f9qmfvbtsqi1w6lonhdg9h4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2as5bsywt2w6j5bxpmgbpueo6.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2b29e4s0mi7zi8wl0rh3rfzeg.08bvbkv.rcg ...\n17.026  cc               202506 202505   0 /usr/bin/cc -m64 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/rustcWNvPV3/symbols.o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.03ezmiww155e2y9bhx16j02r0.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.073wgqeycbd8pfgx1rrw9hiuv.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.07hyvz4debz23bkngurc123tr.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0ainpf94ghwn565eyo7uia7qy.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0mgnjr8xhrtx4gef9w9sbeywf.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0s11x300aj3936agrc9uu9v08.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.16tnxtpx0n36ebbg7b0hf0an4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.17qykxaloia7j4hm82wwrrcal.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1bjttpdft90gojgwjjkckup47.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1c7y9mivcuftk2x2jgkfzm1bd.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1tdx60jvwm98pgfmpdnu8dnfm.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1utow171ind4l0k0jnol7pxnx.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1w2ys22pc5470llgaz9ry9op5.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1yy585xd9ffm3wnvdou2qv7yc.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.25f9qmfvbtsqi1w6lonhdg9h4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2as5bsywt2w6j5bxpmgbpueo6.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2b29e4s0mi7zi8wl0rh3rfzeg.08bvbkv.rcg ...\n17.031  collect2         202507 202506   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.033  ld.lld           202508 202507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66 ...\n17.034  rust-lld         202508 202507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.152  build-script-bu  202526 202194   0 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build-script-build\n17.156  rustc            202528 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pyo3_build_config --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n17.179  git              202532 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.216  containerd-shim  202533 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef delete\n17.219  runc             202539 202533   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476a --log-format json delete --force 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af\n17.256  sh               202547 201826   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth8fb9435\n17.258  ethtool          202548 202547   0 /usr/sbin/ethtool -i veth8fb9435\n17.258  sed              202549 202547   0 /usr/bin/sed -n s/^driver: //p\n17.264  systemd-sysctl   202552 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8fb9435 --prefix=/net/ipv4/neigh/veth8fb9435 --prefix=/net/ipv6/conf/veth8fb9435 --prefix=/net/ipv6/neigh/veth8fb9435\n17.272  16               202553 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n17.286  frpc             202553 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.572  cross            202664 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.573  rustc            202668 202664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.579  rustc            202668 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.593  rustc            202702 202664   0 /home/xmoe/.cargo/bin/rustc -vV\n17.599  rustc            202702 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.609  cargo            202720 202664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.614  cargo            202720 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.624  rustc            202729 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.634  rustc            202731 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.648  rustc            202735 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.710  riscv64-linux-g  202740 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d ...\n17.711  cc1              202741 202740   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o ...\n17.740  mkdir            202742 185444   0 /usr/bin/mkdir -p lib\n17.742  ar               202743 185444   0 /tmp/native-trace-167308-1783993149912/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n17.743  ar               202744 202743   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n17.760  rustc            202745 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.775  rustc            202747 202664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.781  rustc            202747 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.793  docker           202759 202664   0 /usr/bin/docker --help\n17.805  docker           202770 202664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.817  runc             202781 1599     0 /usr/bin/runc --version\n17.819  docker-init      202787 1599     0 /usr/bin/docker-init --version\n17.821  docker           202788 202664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.832  runc             202800 1599     0 /usr/bin/runc --version\n17.835  docker-init      202806 1599     0 /usr/bin/docker-init --version\n17.857  rustup           202807 202664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.863  rustup           202816 202664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.886  rustup           202825 202664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.910  uname            202834 202664   0 /usr/bin/uname -r\n17.926  docker           202835 202664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.958  systemd-sysctl   202848 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdf72c94 --prefix=/net/ipv4/neigh/vethdf72c94 --prefix=/net/ipv6/conf/vethdf72c94 --prefix=/net/ipv6/neigh/vethdf72c94\n17.958  systemd-sysctl   202849 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth332cd71 --prefix=/net/ipv4/neigh/veth332cd71 --prefix=/net/ipv6/conf/veth332cd71 --prefix=/net/ipv6/neigh/veth332cd71\n17.966  cross            202850 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.968  rustc            202853 202850   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.970  cross            202854 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.973  rustc            202857 202854   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.978  rustc            202853 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.980  rustc            202857 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.981  containerd-shim  202874 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 start\n17.985  containerd-shim  202881 202874   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 -address /var/run/docker/containerd/containerd.sock\n17.985  runc             202882 198094   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 --log-format json --systemd-cgroup kill --all 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46 9\n17.989  runc             202903 202881   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6\n17.992  rustc            202910 202854   0 /home/xmoe/.cargo/bin/rustc -vV\n17.994  rustc            202909 202850   0 /home/xmoe/.cargo/bin/rustc -vV\n17.995  runc             202911 198094   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 --log-format json --systemd-cgroup delete 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46\n17.997  exe              202935 202903   0 /proc/self/exe init\n17.999  rustc            202909 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.001  rustc            202910 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.009  cargo            202939 202850   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.011  cargo            202940 202854   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.016  cargo            202939 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.016  cargo            202940 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.026  rustc            202964 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.035  rustc            202966 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.038  rustc            202967 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.046  rustc            202970 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.048  exe              202973 202903   0 /proc/1599/exe -exec-root=/var/run/docker a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 d7da31e8f8e1\n18.050  rustc            202974 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.058  rustc            202983 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.069  exe              202993 1599     0 /proc/self/exe /var/run/docker/netns/65d4070b5c48 all false\n18.124  runc             203010 202881   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --log-format json --systemd-cgroup start a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6\n18.130  sh               202958 202881   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.131  cargo            203016 202958   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.141  cargo-native-tr  203016 202958   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.145  cargo            203017 203016   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.156  rustc            203018 203017   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.168  rustc            203022 203017   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.172  containerd-shim  203023 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 delete\n18.175  runc             203030 203023   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae4 --log-format json delete --force 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46\n18.208  systemd-sysctl   203039 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd0867e0 --prefix=/net/ipv4/neigh/vethd0867e0 --prefix=/net/ipv6/conf/vethd0867e0 --prefix=/net/ipv6/neigh/vethd0867e0\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/uncased-75d093de25ddc81b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 199673,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
  "pid": 199673,
  "ppid": 199477,
  "root_cargo_pid": 199477,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
  "build_script_root_pid": 199673,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199674,
  "ppid": 199673,
  "root_cargo_pid": 199477,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_build_script_out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
  "build_script_root_pid": 199673,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199678,
  "ppid": 199673,
  "root_cargo_pid": 199477,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_build_script_out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "uncased",
  "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "event_id": "bsrun:1b15d5931307b145:f506a86cb9642b5d:2640f7a39d4cfbf2",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
  "out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
  "success": true,
  "target": null,
  "version": "0.9.10",
  "_owner": {
    "crate": "uncased",
    "version": "0.9.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
    "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
  "build_script_root_pid": 199673,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199674,
  "ppid": 199673,
  "root_cargo_pid": 199477,
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
  "build_script_root_pid": 199673,
  "build_script_target_dir": "uncased-75d093de25ddc81b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 199678,
  "ppid": 199673,
  "root_cargo_pid": 199477,
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
  "time": "2026-07-14T01:40:42.249129+00:00",
  "crate": "uncased",
  "version": "0.9.10",
  "architecture": "riscv64",
  "duration_seconds": 29.028650091961026,
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
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "manifest_path": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10/Cargo.toml"
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "workspace_root": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
          "name": "uncased",
          "version": "0.9.10",
          "manifest_path": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10"
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
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 199606,
      "ppid": 199591,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:922d4a293d4f300b:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
      "pid": 199606,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:2b1248427a077d4e:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "fc98b494b56d9bd2b60f6d163fa0fe4662dd351e251e6eb4ddcacd4b96d639aa",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:ee4b1e4df54121e5:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "98c4bc6ceaa1e8a30b838e0cb46e62e6b879081e1851b743a0a4a6d7eeba2b83",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:0ae75b1f5c389619:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "b7a958dda6fb43a2f3acbf4d1fbe387f10fc0ba1f989729fd538d8cfb28e9202",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:111dbe257e8bc987:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "7b38543495a8a3571a12427dae67170823f0c71552f85b876f59dbb43c59e21d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:496b31fde1fae5ba:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "8c290bf5de753dd4f2a147bc66b17faf3acdfd203d47bedb3ba4ac1e7f4752f5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:3d65315e1a0b8567:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "57b3f8c46c049f7418f98d34e31defcda914cde23aecb4fb285645478ab7ae75",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "used:cc:582b699f3345e1bd:a51f5184e8e9be07:d9e089d500bf06f9",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b",
      "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
      "pid": 199606,
      "sha256": "d026706d111433c3ec386f86441995a7d2260bf60592a3732e01a10ac45fe1a4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "cargo_pkg_name": "uncased",
      "cargo_pkg_version": "0.9.10",
      "context_path": "/tmp/native-trace-198253-1783993219093/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-198253-1783993219093/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 199606,
      "ppid": 199591,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
        "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/raw-dylibs",
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
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
        "/target/debug/build/uncased-75d093de25ddc81b",
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
          "directory": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/rustcKNAOwY/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0ku924xpxhkoipj1vofke72nc.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.0u1c7pttsfjv93k6o5aubmev8.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.3y7n0r55r5e8ne1cln0iqykws.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.7rob0b73brbpnrgxxsvu1eln4.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.bxe91w1isnap911r8aq4psytj.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.eesycgkep5nj6goys3toouhnq.1vwm6qe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/uncased-75d093de25ddc81b",
          "kind": "object",
          "path": "/target/debug/build/uncased-75d093de25ddc81b/build_script_build-75d093de25ddc81b.dgjk4mspurlycz05xa1pevy1e.1vwm6qe.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-199606-1783993224406136303.map",
      "pid": 199606,
      "ppid": 199591,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-199606-1783993224406136303.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
      "parsed_event_count": 1234,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1236,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " /usr/bin/docker-init --version\n13.206  rustup           201722 201573   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.213  rustup           201731 201573   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.242  rustup           201740 201573   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.266  rustc            201750 201632   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.268  aarch64-linux-g  201749 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c\n13.268  uname            201751 201573   0 /usr/bin/uname -r\n13.269  cc1              201752 201749   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -mlittle-endian ...\n13.291  docker           201754 201573   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.294  rustc            201758 201585   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.301  rustc            201758 201585   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.305  mkdir            201775 183581   0 /usr/bin/mkdir -p lib\n13.308  ar               201776 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n13.311  ar               201777 201776   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n13.317  docker           201781 201585   0 /usr/bin/docker --help\n13.333  docker           201793 201585   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.349  runc             201804 1599     0 /usr/bin/runc --version\n13.354  docker-init      201810 1599     0 /usr/bin/docker-init --version\n13.359  docker           201811 201585   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.362  systemd-sysctl   201819 201812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb607043 --prefix=/net/ipv4/neigh/vethb607043 --prefix=/net/ipv6/conf/vethb607043 --prefix=/net/ipv6/neigh/vethb607043\n13.367  systemd-sysctl   201820 201818   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth3a82113 --prefix=/net/ipv4/neigh/veth3a82113 --prefix=/net/ipv6/conf/veth3a82113 --prefix=/net/ipv6/neigh/veth3a82113\n13.379  runc             201844 1599     0 /usr/bin/runc --version\n13.390  docker-init      201860 1599     0 /usr/bin/docker-init --version\n13.390  containerd-shim  201859 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e start\n13.394  containerd-shim  201866 201859   0 \n13.398  runc             201877 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n13.406  exe              201884 201877   0 /proc/self/exe init\n13.417  rustup           201887 201585   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.425  rustup           201903 201585   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.444  exe              201912 201877   0 /proc/1599/exe -exec-root=/var/run/docker 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e d7da31e8f8e1\n13.454  rustup           201919 201585   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.470  exe              201929 1599     0 /proc/self/exe /var/run/docker/netns/731df16afe4b all false\n13.483  uname            201938 201585   0 /usr/bin/uname -r\n13.504  docker           201943 201585   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.530  runc             201954 201866   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b3 --log-format json --systemd-cgroup start 31b91644e46e5658ec25133babbc7d140416355214631e4d20e00fc17b35131e\n13.538  sh               201897 201866   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.540  cargo            201960 201897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.550  systemd-sysctl   201962 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth203181a --prefix=/net/ipv4/neigh/veth203181a --prefix=/net/ipv6/conf/veth203181a --prefix=/net/ipv6/neigh/veth203181a\n13.550  systemd-sysctl   201961 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdffa2b9 --prefix=/net/ipv4/neigh/vethdffa2b9 --prefix=/net/ipv6/conf/vethdffa2b9 --prefix=/net/ipv6/neigh/vethdffa2b9\n13.556  cargo-native-tr  201960 201897   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n13.564  cargo            201963 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.579  rustc            201964 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.589  containerd-shim  201966 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de start\n13.593  containerd-shim  201974 201966   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de -address /var/run/docker/containerd/containerd.sock\n13.594  rustc            201970 201963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.598  runc             201983 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n13.607  exe              201993 201983   0 /proc/self/exe init\n13.614  execsnoop        201996 201960   0 /usr/local/bin/execsnoop -t\n13.615  python3          201996 201960   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.638  exe              202006 201983   0 /proc/1599/exe -exec-root=/var/run/docker a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de d7da31e8f8e1\n13.668  exe              202014 1599     0 /proc/self/exe /var/run/docker/netns/34b60308b67c all false\n13.717  runc             202025 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup kill --all db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a 9\n13.735  runc             202032 201974   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d27 --log-format json --systemd-cgroup start a989943dc2ba8e53ad7f75dacb0fa7a80c91b081fabdbae94cce0284d278d9de\n13.738  runc             202038 191912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 --log-format json --systemd-cgroup delete db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n13.742  sh               202000 201974   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.744  cargo            202044 202000   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.761  cargo-native-tr  202044 202000   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.765  cargo            202045 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.777  rustc            202046 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.791  rustc            202048 202045   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.811  execsnoop        202052 202044   0 /usr/local/bin/execsnoop -t\n13.813  python3          202052 202044   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n13.881  runc             202055 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2327736004 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n13.888  exe              202062 202055   0 /proc/self/exe init\n13.913  curl             202064 202055   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n13.973  containerd-shim  202071 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab304108 delete\n13.977  runc             202078 202071   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529 --log-format json delete --force db5a5669dc7736c2d2d3d9d1a796dcb768c797463983cc6215dab3041083529a\n13.998  aarch64-linux-g  202084 183581   0 /usr/bin/aarch64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c\n14.000  cc1              202085 202084   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch aarch64-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -mlittle-endian ...\n14.010  systemd-sysctl   202086 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda73173 --prefix=/net/ipv4/neigh/vethda73173 --prefix=/net/ipv6/conf/vethda73173 --prefix=/net/ipv6/neigh/vethda73173\n14.036  mkdir            202087 183581   0 /usr/bin/mkdir -p lib\n14.038  ar               202088 183581   0 /tmp/native-trace-167169-1783993149691/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n14.040  ar               202089 202088   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n14.277  make             202090 168808   0 /tmp/native-trace-167169-1783993149691/shims/make install_lib_static install_include -j 16\n14.278  make             202091 202090   0 /usr/bin/make install_lib_static install_include -j 16\n14.301  install          202092 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.301  install          202093 202091   0 /usr/bin/install -c -d /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n14.302  sh               202095 202091   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/aarch64-unknown-linux-gnu/debug/build/tik\n14.302  sh               202094 202091   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/aarch64-unknown-linux-gnu/deb\n14.304  install          202096 202095   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/include/jemalloc\n14.304  install          202097 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.336  install          202098 202094   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/aarch64-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-20f5c17968406e28/out/lib\n14.370  rustc            202100 168219   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n14.878  runc             202107 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup kill --all 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be 9\n14.897  runc             202113 193711   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 --log-format json --systemd-cgroup delete 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n14.978  sh               202119 2147557   0 /bin/sh -c which ps\n14.979  which            202119 2147557   0 /usr/bin/which ps\n14.982  sh               202120 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n14.984  ps               202120 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n15.012  sh               202121 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n15.014  cpuUsage.sh      202121 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n15.015  sed              202122 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n15.018  cat              202123 202121   0 /usr/bin/cat /proc/2240539/stat\n15.020  cat              202124 202121   0 /usr/bin/cat /proc/4193716/stat\n15.021  sleep            202125 202121   0 /usr/bin/sleep 1\n15.079  containerd-shim  202126 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4 delete\n15.082  runc             202133 202126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7b --log-format json delete --force 6a62a9033d8cf39879350fac2729baaf22d78fb0f8723bc175b424621f4ef7be\n15.126  systemd-sysctl   202138 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd6275bb --prefix=/net/ipv4/neigh/vethd6275bb --prefix=/net/ipv6/conf/vethd6275bb --prefix=/net/ipv6/neigh/vethd6275bb\n15.194  rustup           202139 193151   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n15.277  powerpc64le-lin  202148 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d src/jemalloc.c ...\n15.279  cc1              202149 202148   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.d -msecure-plt ...\n15.310  mkdir            202150 186442   0 /usr/bin/mkdir -p lib\n15.311  ar               202151 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n15.313  ar               202152 202151   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n15.617  runc             202153 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup kill --all 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 9\n15.636  runc             202159 192290   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 --log-format json --systemd-cgroup delete 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n15.842  containerd-shim  202165 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918 delete\n15.845  runc             202171 202165   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d463 --log-format json delete --force 22b4e6ea1acd6c1e664dad78fa052fc33c9cd7c60dbfeec99b4b556b918d4630\n15.882  systemd-sysctl   202177 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha86f86b --prefix=/net/ipv4/neigh/vetha86f86b --prefix=/net/ipv6/conf/vetha86f86b --prefix=/net/ipv6/neigh/vetha86f86b\n15.933  cargo            202178 201960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.948  rustc            202179 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.968  rustc            202185 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.73/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=eb116b70676b3078 ...\n16.023  sed              202189 202121   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.026  cat              202190 202121   0 /usr/bin/cat /proc/2240539/stat\n16.028  cat              202192 202121   0 /usr/bin/cat /proc/4193716/stat\n16.096  cargo            202194 202044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n16.115  rustc            202195 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.137  rustc            202202 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.137  rustc            202203 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name once_cell --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.21.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"race\" ...\n16.298  powerpc64le-lin  202217 186442   0 /usr/bin/powerpc64le-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.pic.o -o src/jemalloc.pic.d src/jemalloc.c ...\n16.300  cc1              202218 202217   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -I include -I include -imultiarch powerpc64le-linux-gnu -MM -MT src/jemalloc.pic.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o src/jemalloc.pic.d -msecure-plt ...\n16.333  mkdir            202224 186442   0 /usr/bin/mkdir -p lib\n16.335  ar               202225 186442   0 /tmp/native-trace-167505-1783993150345/shims/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n16.336  ar               202226 202225   0 /usr/bin/ar crus lib/libjemalloc_pic.a src/jemalloc.pic.o src/arena.pic.o src/background_thread.pic.o src/base.pic.o src/bin.pic.o src/bin_info.pic.o src/bitmap.pic.o src/buf_writer.pic.o src/cache_bin.pic.o src/ckh.pic.o src/counter.pic.o src/ctl.pic.o src/decay.pic.o src/div.pic.o src/ecache.pic.o src/edata.pic.o src/edata_cache.pic.o ...\n16.355  cc               202229 202202   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.357  cc               202230 202229   0 /usr/bin/cc -m64 /target/debug/build/target-lexicon-a4341170caa0e707/rustcWjTfu1/symbols.o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.build_script_build.9a69314f9869656f-cgu. /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707.bk8u7v6ru515blach9f10bzyw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n16.361  collect2         202232 202230   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.362  ld.lld           202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/target-lexicon-a4341170caa0e707/build_script_build-a4341170caa0e707 ...\n16.364  rust-lld         202233 202232   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVmtBwT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.426  build-script-bu  202259 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n16.427  build-script-bu  202260 202194   0 /target/debug/build/target-lexicon-a4341170caa0e707/build-script-build\n16.429  rustc            202261 202259   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.430  rustc            202263 202260   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.444  rustc            202266 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.448  rustc            202270 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name target_lexicon --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/target-lexicon-0.12.16/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arch_zkasm\", \"default\", \"serde\", \"serde_support\", \"std\")) ...\n16.491  rustc            202279 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=c1cd10384c51484d ...\n16.556  cc               202302 202279   0 /tmp/native-trace-201960-1783993237281/shims/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n16.558  cc               202303 202302   0 /usr/bin/cc -m64 /target/debug/build/psm-b8491c55b4fe6077/rustcYnT1Wz/symbols.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.0qymk5uimotfmjuzkdny9f00f.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.2f6afxfr5p3uvc5rrmvtwl0fp.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6cne00e8pawk00azv6yyxuawq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.6jviwmxrdnegnitq6dkys41ng.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.75k574cwqpzj2icfwqm839xiq.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.93tem34l024zmd4x9dflex8sx.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.9l0cm14iuch8d7ykzaforujp0.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.amlldk3egap1rveyvw3dlqjku.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ar4t2tyu2fbgl7xlbq2t3nzgz.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.avws2mgws69k5kg8h4ke1h6zu.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.axcbkr0mp41cnowuc09rswm7s.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.cxffip0wjzccfvkodc4uuaoz8.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.da5sirulez6gpnhwoa9uu3aqs.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.dp8vrmsaobp8au64r37h5p5ka.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ea3bm7qcibyipg0c687hvam95.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.eba46r3q5m7c0dmdtjahbrg8e.10tnw9y.rcgu.o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077.ebjfhoqsemlff2vqirsz3nufe.10tnw9y.rcgu.o ...\n16.561  collect2         202304 202303   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.563  ld.lld           202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/psm-b8491c55b4fe6077/build_script_build-b8491c55b4fe6077 ...\n16.564  rust-lld         202305 202304   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVqUlo.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.588  make             202328 170525   0 /tmp/native-trace-167505-1783993150345/shims/make install_lib_static install_include -j 16\n16.589  make             202329 202328   0 /usr/bin/make install_lib_static install_include -j 16\n16.612  install          202334 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.614  install          202335 202329   0 /usr/bin/install -c -d /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n16.615  sh               202336 202329   0 /bin/sh -c for l in lib/libjemalloc.a lib/libjemalloc_pic.a; do \\\\necho \"/usr/bin/install -c -m 755 $l /target/powerpc64le-unknown-linux-gnu\n16.617  install          202338 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.617  sh               202337 202329   0 /bin/sh -c for h in include/jemalloc/jemalloc.h; do \\\\necho \"/usr/bin/install -c -m 644 $h /target/powerpc64le-unknown-linux-gnu/debug/build\n16.617  install          202339 202337   0 /usr/bin/install -c -m 644 include/jemalloc/jemalloc.h /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/include/jemalloc\n16.634  rustc            202341 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n16.635  build-script-bu  202343 202178   0 /target/debug/build/psm-b8491c55b4fe6077/build-script-build\n16.639  powerpc64le-lin  202344 202343   0 /usr/bin/powerpc64le-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -fno-omit-frame-pointer -m64 -Wall -Wextra -xassembler-with-cpp -DCFG_TARGET_OS_linux -DCFG_TARGET_ARCH_powerpc64 -DCFG_TARGET_ENV_gnu -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o -c src/arch/powerpc64_openpower.s\n16.640  cc1              202346 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -lang-asm -quiet -imultiarch powerpc64le-linux-gnu -D CFG_TARGET_OS_linux -D CFG_TARGET_ARCH_powerpc64 -D CFG_TARGET_ENV_gnu src/arch/powerpc64_openpower.s -msecure-plt -m64 -mcpu=power8 -Wall -Wextra -ffunction-sections -fdata-sections ...\n16.645  as               202351 202344   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as --gdwarf2 -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o /tmp/ccKOqcNw.s\n16.645  install          202350 202336   0 /usr/bin/install -c -m 755 lib/libjemalloc_pic.a /target/powerpc64le-unknown-linux-gnu/debug/build/tikv-jemalloc-sys-792224d3c84e6b99/out/lib\n16.651  powerpc64le-lin  202352 202343   0 /usr/bin/powerpc64le-linux-gnu-ar cq /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/src/arch/powerpc64_openpower.o\n16.654  powerpc64le-lin  202354 202343   0 /usr/bin/powerpc64le-linux-gnu-ar s /target/powerpc64le-unknown-linux-gnu/debug/build/psm-95dd3c80e9e1d924/out/libpsm_s.a\n16.661  rustc            202357 202178   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name psm --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e8967af7065dad73 ...\n16.680  rustc            202362 168713   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tikv_jemalloc_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"background_threads_runtime_support\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n16.997  runc             202478 197549   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef --log-format json --systemd-cgroup kill --all 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af 9\n17.015  runc             202499 197549   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef --log-format json --systemd-cgroup delete 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af\n17.025  cc               202505 202341   0 /tmp/native-trace-202044-1783993237486/shims/cc -m64 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/rustcWNvPV3/symbols.o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.03ezmiww155e2y9bhx16j02r0.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.073wgqeycbd8pfgx1rrw9hiuv.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.07hyvz4debz23bkngurc123tr.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0ainpf94ghwn565eyo7uia7qy.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0mgnjr8xhrtx4gef9w9sbeywf.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0s11x300aj3936agrc9uu9v08.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.16tnxtpx0n36ebbg7b0hf0an4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.17qykxaloia7j4hm82wwrrcal.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1bjttpdft90gojgwjjkckup47.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1c7y9mivcuftk2x2jgkfzm1bd.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1tdx60jvwm98pgfmpdnu8dnfm.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1utow171ind4l0k0jnol7pxnx.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1w2ys22pc5470llgaz9ry9op5.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1yy585xd9ffm3wnvdou2qv7yc.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.25f9qmfvbtsqi1w6lonhdg9h4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2as5bsywt2w6j5bxpmgbpueo6.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2b29e4s0mi7zi8wl0rh3rfzeg.08bvbkv.rcg ...\n17.026  cc               202506 202505   0 /usr/bin/cc -m64 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/rustcWNvPV3/symbols.o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.03ezmiww155e2y9bhx16j02r0.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.073wgqeycbd8pfgx1rrw9hiuv.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.07hyvz4debz23bkngurc123tr.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0ainpf94ghwn565eyo7uia7qy.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0mgnjr8xhrtx4gef9w9sbeywf.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.0s11x300aj3936agrc9uu9v08.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.16tnxtpx0n36ebbg7b0hf0an4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.17qykxaloia7j4hm82wwrrcal.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1bjttpdft90gojgwjjkckup47.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1c7y9mivcuftk2x2jgkfzm1bd.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1tdx60jvwm98pgfmpdnu8dnfm.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1utow171ind4l0k0jnol7pxnx.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1w2ys22pc5470llgaz9ry9op5.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.1yy585xd9ffm3wnvdou2qv7yc.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.25f9qmfvbtsqi1w6lonhdg9h4.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2as5bsywt2w6j5bxpmgbpueo6.08bvbkv.rcg /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66.2b29e4s0mi7zi8wl0rh3rfzeg.08bvbkv.rcg ...\n17.031  collect2         202507 202506   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.033  ld.lld           202508 202507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build_script_build-8119597e8f9c0a66 ...\n17.034  rust-lld         202508 202507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjKcsZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.152  build-script-bu  202526 202194   0 /target/debug/build/pyo3-build-config-8119597e8f9c0a66/build-script-build\n17.156  rustc            202528 202194   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pyo3_build_config --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"abi3\", \"abi3-py310\", \"abi3-py311\", \"abi3-py37\", \"abi3-py38\", \"abi3-py39\", \"default\", \"extension-module\", \"p ...\n17.179  git              202532 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n17.216  containerd-shim  202533 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef delete\n17.219  runc             202539 202533   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476a --log-format json delete --force 134de7a2a2c372c454181fb1c2939238e6d75a36a1d9b16367ae12434ef476af\n17.256  sh               202547 201826   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth8fb9435\n17.258  ethtool          202548 202547   0 /usr/sbin/ethtool -i veth8fb9435\n17.258  sed              202549 202547   0 /usr/bin/sed -n s/^driver: //p\n17.264  systemd-sysctl   202552 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth8fb9435 --prefix=/net/ipv4/neigh/veth8fb9435 --prefix=/net/ipv6/conf/veth8fb9435 --prefix=/net/ipv6/neigh/veth8fb9435\n17.272  16               202553 1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n17.286  frpc             202553 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.572  cross            202664 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n17.573  rustc            202668 202664   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.579  rustc            202668 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.593  rustc            202702 202664   0 /home/xmoe/.cargo/bin/rustc -vV\n17.599  rustc            202702 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.609  cargo            202720 202664   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.614  cargo            202720 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n17.624  rustc            202729 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.634  rustc            202731 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.648  rustc            202735 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.710  riscv64-linux-g  202740 185444   0 /usr/bin/riscv64-linux-gnu-gcc -MM -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -D_GNU_SOURCE -D_REENTRANT -Iinclude -Iinclude -MT src/jemalloc.o -o src/jemalloc.d ...\n17.711  cc1              202741 202740   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -I include -I include -imultilib . -imultiarch riscv64-linux-gnu -MM -MT src/jemalloc.o -D _GNU_SOURCE -D _REENTRANT src/jemalloc.c -o ...\n17.740  mkdir            202742 185444   0 /usr/bin/mkdir -p lib\n17.742  ar               202743 185444   0 /tmp/native-trace-167308-1783993149912/shims/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n17.743  ar               202744 202743   0 /usr/bin/ar crus lib/libjemalloc.a src/jemalloc.o src/arena.o src/background_thread.o src/base.o src/bin.o src/bin_info.o src/bitmap.o src/buf_writer.o src/cache_bin.o src/ckh.o src/counter.o src/ctl.o src/decay.o src/div.o src/ecache.o src/edata.o src/edata_cache.o ...\n17.760  rustc            202745 202720   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.775  rustc            202747 202664   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.781  rustc            202747 202664   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.793  docker           202759 202664   0 /usr/bin/docker --help\n17.805  docker           202770 202664   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.817  runc             202781 1599     0 /usr/bin/runc --version\n17.819  docker-init      202787 1599     0 /usr/bin/docker-init --version\n17.821  docker           202788 202664   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.832  runc             202800 1599     0 /usr/bin/runc --version\n17.835  docker-init      202806 1599     0 /usr/bin/docker-init --version\n17.857  rustup           202807 202664   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.863  rustup           202816 202664   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.886  rustup           202825 202664   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.910  uname            202834 202664   0 /usr/bin/uname -r\n17.926  docker           202835 202664   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.958  systemd-sysctl   202848 201831   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethdf72c94 --prefix=/net/ipv4/neigh/vethdf72c94 --prefix=/net/ipv6/conf/vethdf72c94 --prefix=/net/ipv6/neigh/vethdf72c94\n17.958  systemd-sysctl   202849 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth332cd71 --prefix=/net/ipv4/neigh/veth332cd71 --prefix=/net/ipv6/conf/veth332cd71 --prefix=/net/ipv6/neigh/veth332cd71\n17.966  cross            202850 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n17.968  rustc            202853 202850   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.970  cross            202854 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.973  rustc            202857 202854   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.978  rustc            202853 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.980  rustc            202857 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.981  containerd-shim  202874 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 start\n17.985  containerd-shim  202881 202874   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 -address /var/run/docker/containerd/containerd.sock\n17.985  runc             202882 198094   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 --log-format json --systemd-cgroup kill --all 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46 9\n17.989  runc             202903 202881   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6\n17.992  rustc            202910 202854   0 /home/xmoe/.cargo/bin/rustc -vV\n17.994  rustc            202909 202850   0 /home/xmoe/.cargo/bin/rustc -vV\n17.995  runc             202911 198094   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 --log-format json --systemd-cgroup delete 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46\n17.997  exe              202935 202903   0 /proc/self/exe init\n17.999  rustc            202909 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.001  rustc            202910 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.009  cargo            202939 202850   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.011  cargo            202940 202854   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.016  cargo            202939 202850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.016  cargo            202940 202854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n18.026  rustc            202964 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.035  rustc            202966 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.038  rustc            202967 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.046  rustc            202970 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.048  exe              202973 202903   0 /proc/1599/exe -exec-root=/var/run/docker a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6 d7da31e8f8e1\n18.050  rustc            202974 202940   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.058  rustc            202983 202939   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.069  exe              202993 1599     0 /proc/self/exe /var/run/docker/netns/65d4070b5c48 all false\n18.124  runc             203010 202881   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a --log-format json --systemd-cgroup start a70dd4e48f102ba873e556a457069b6d83375ca961f9e62585901c7c80a2c1c6\n18.130  sh               202958 202881   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.131  cargo            203016 202958   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.141  cargo-native-tr  203016 202958   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n18.145  cargo            203017 203016   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.156  rustc            203018 203017   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.168  rustc            203022 203017   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.172  containerd-shim  203023 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a1996 delete\n18.175  runc             203030 203023   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae4 --log-format json delete --force 6008dcd9b5cd2e9e40c667f86b5758be43b0220d272efc8ea7bb79a19961ae46\n18.208  systemd-sysctl   203039 201826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethd0867e0 --prefix=/net/ipv4/neigh/vethd0867e0 --prefix=/net/ipv6/conf/vethd0867e0 --prefix=/net/ipv6/neigh/vethd0867e0\n"
    },
    {
      "argv": [
        "/target/debug/build/uncased-75d093de25ddc81b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199673,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
      "pid": 199673,
      "ppid": 199477,
      "root_cargo_pid": 199477,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199673,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199674,
      "ppid": 199673,
      "root_cargo_pid": 199477,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 199673,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199678,
      "ppid": 199673,
      "root_cargo_pid": 199477,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "uncased",
      "cwd": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "event_id": "bsrun:1b15d5931307b145:f506a86cb9642b5d:2640f7a39d4cfbf2",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/uncased-75d093de25ddc81b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
      "out_dir": "/target/debug/build/uncased-75d093de25ddc81b/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
      "success": true,
      "target": null,
      "version": "0.9.10",
      "_owner": {
        "crate": "uncased",
        "version": "0.9.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10#uncased@0.9.10",
        "manifest_dir": "/tmp/crate-build-riscv64-azr8aopi/src/uncased-0.9.10",
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
      "build_script_root_pid": 199673,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199674,
      "ppid": 199673,
      "root_cargo_pid": 199477,
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
      "build_script_root_pid": 199673,
      "build_script_target_dir": "uncased-75d093de25ddc81b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 199678,
      "ppid": 199673,
      "root_cargo_pid": 199477,
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
