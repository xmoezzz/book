# `chrono-tz` `0.10.4`

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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
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
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
    "/target/debug/build/chrono-tz-b85d549251c55a98",
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
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-214430-1783993283618939854.map",
  "pid": 214430,
  "ppid": 214413,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-214430-1783993283618939854.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.2.0",
      "name": "autocfg",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
      "name": "byteorder",
      "version": "1.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono@0.4.38",
      "name": "chrono",
      "version": "0.4.38",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
      "name": "chrono-tz",
      "version": "0.10.4",
      "manifest_path": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono-tz-build@0.5.0",
      "name": "chrono-tz-build",
      "version": "0.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
      "name": "fastrand",
      "version": "2.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
      "name": "num-traits",
      "version": "0.2.18",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parse-zoneinfo@0.4.1",
      "name": "parse-zoneinfo",
      "version": "0.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.12.1",
      "name": "phf",
      "version": "0.12.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.12.1",
      "name": "phf_codegen",
      "version": "0.12.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.12.1",
      "name": "phf_generator",
      "version": "0.12.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.12.1",
      "name": "phf_shared",
      "version": "0.12.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.80",
      "name": "proc-macro2",
      "version": "1.0.80",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.36",
      "name": "quote",
      "version": "1.0.36",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.197",
      "name": "serde",
      "version": "1.0.197",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.197",
      "name": "serde_derive",
      "version": "1.0.197",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.176",
      "name": "serde_test",
      "version": "1.0.176",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@1.0.1",
      "name": "siphasher",
      "version": "1.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.59",
      "name": "syn",
      "version": "2.0.59",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tzfile@0.1.3",
      "name": "tzfile",
      "version": "0.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
    }
  ],
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 214430,
  "ppid": 214413,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:f67ce77a0926d025:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
  "pid": 214430,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:f5e03c3f97148e18:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "3f44b34747f774ee92e42e8f7301cdc3565cfbfc588f6db011b4fde595173b61",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:f625bd3e1908f78f:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "7625074197c276019039eecf31d735aa3711a27edfd00ef8cf5538bc21927f43",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:fd40ce395de1dd62:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "b92faa7eb749e24c3da632116d76011b554ce9007f70ff723f571d4f019c3dfc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:9be3628c25293c37:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "bb1344f8d97806df77b268553c11d91458a2d8818e0941e53a3f99d0c3666b2b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:b7b7de4a39a4d7f6:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "ab52ec4323aed1b3bf0c126a64d4f755108bd9ee178dcb88d8978263385b9f60",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "used:cc:6bde491006586088:308daaf46ee0e957:bf58ef438fa3a928",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
  "pid": 214430,
  "sha256": "e9bfdebd4a0234a4f19dc176c8fb0fb8e3dfabeb49b6dd86470fa9c980077c2d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
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
  "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "cargo_pkg_name": "chrono-tz",
  "cargo_pkg_version": "0.10.4",
  "context_path": "/tmp/native-trace-214195-1783993281403/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-214195-1783993281403/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 214430,
  "ppid": 214413,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
    "/target/debug/build/chrono-tz-b85d549251c55a98",
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
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
      "kind": "object",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-214430-1783993283618939854.map",
  "pid": 214430,
  "ppid": 214413,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-214430-1783993283618939854.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "exit_code": 0,
  "kind": "exec",
  "pid": 214537,
  "ppid": 214509,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.18",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "event_id": "used:cc:868aabdfedc436c3:0f1e867ebeba8374:b661e894909a6a6d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
  "path": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
  "pid": 214537,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.18",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "event_id": "used:cc:868aabdfedc436c3:524d55c71fe107ba:b661e894909a6a6d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
  "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
  "pid": 214537,
  "sha256": "ec603eb0c38b936a4ba9e6c49956563f3e660063e4622556671851ced3368567",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.18",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "event_id": "used:cc:868aabdfedc436c3:028b9b8a57be3eb5:b661e894909a6a6d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
  "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
  "pid": 214537,
  "sha256": "ad363273c99273de7263901d7ea523c0bc64892a00470e1f1795e9bd17ff9031",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
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
  "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.18",
  "context_path": "/tmp/native-trace-214195-1783993281403/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-214195-1783993281403/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 214537,
  "ppid": 214509,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y",
    "/target/debug/build/num-traits-8cdeb73dca624620",
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
      "directory": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y",
      "kind": "object",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-8cdeb73dca624620",
      "kind": "object",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-8cdeb73dca624620",
      "kind": "object",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-214537-1783993283866220799.map",
  "pid": 214537,
  "ppid": 214509,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-214537-1783993283866220799.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 20

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

#### Record 21

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 1191,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1192,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n18.805  runc             220579 220568   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d99b48bf02e028923c1160684581df1a74f8a69b2a235ebba1604f12060119b --log-format json delete --force d99b48bf02e028923c1160684581df1a74f8a69b2a235ebba1604f12060119be\n18.820  runc             220593 1599     0 /usr/bin/runc --version\n18.827  docker-init      220602 1599     0 /usr/bin/docker-init --version\n18.830  docker           220603 220315   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.842  containerd-shim  220611 1663     0 \n18.842  runc             220621 220611   0 \n18.851  runc             220631 1599     0 \n18.857  docker-init      220638 1599     0 /usr/bin/docker-init --version\n18.876  rustc            220640 220433   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n18.878  systemd-sysctl   220641 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb9540d3 --prefix=/net/ipv4/neigh/vethb9540d3 --prefix=/net/ipv6/conf/vethb9540d3 --prefix=/net/ipv6/neigh/vethb9540d3\n18.895  rustup           220646 220315   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.906  rustup           220655 220315   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.921  rustc            220665 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n18.946  systemd-sysctl   220670 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha8a8f52 --prefix=/net/ipv4/neigh/vetha8a8f52 --prefix=/net/ipv6/conf/vetha8a8f52 --prefix=/net/ipv6/neigh/vetha8a8f52\n18.948  rustup           220675 220315   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.986  uname            220688 220315   0 /usr/bin/uname -r\n19.014  cc               220689 220221   0 /tmp/native-trace-219340-1783993297394/shims/cc -m64 /target/debug/build/clang-sys-6f971d4cb8e593f1/rustcLYI9CM/symbols.o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.build_script_build.e1f45aacd1af39e3-cgu.0.rcg /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.44ovr9ku5hu9qhasl4b0t7d4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libglob-a91c897b77dd6906.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.015  cc               220691 220689   0 /usr/bin/cc -m64 /target/debug/build/clang-sys-6f971d4cb8e593f1/rustcLYI9CM/symbols.o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.build_script_build.e1f45aacd1af39e3-cgu.0.rcg /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.44ovr9ku5hu9qhasl4b0t7d4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libglob-a91c897b77dd6906.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.023  rustc            220687 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.027  collect2         220696 220691   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.029  rustc            220695 218062   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bindgen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.71.1/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n19.032  ld.lld           220697 220696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1 ...\n19.037  rust-lld         220697 220696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.046  docker           220705 220315   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.133  systemd-sysctl   220738 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a589f5 --prefix=/net/ipv4/neigh/veth7a589f5 --prefix=/net/ipv6/conf/veth7a589f5 --prefix=/net/ipv6/neigh/veth7a589f5\n19.134  systemd-sysctl   220739 220642   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf0c1b76 --prefix=/net/ipv4/neigh/vethf0c1b76 --prefix=/net/ipv6/conf/vethf0c1b76 --prefix=/net/ipv6/neigh/vethf0c1b76\n19.204  containerd-shim  220779 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 start\n19.205  rustc            220768 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.222  cc               220776 220402   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcjX4ByY/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.224  cc               220802 220776   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcjX4ByY/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.233  collect2         220810 220802   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.235  ld.lld           220818 220810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n19.250  rust-lld         220818 220810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.253  containerd-shim  220817 220779   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 -address /var/run/docker/containerd/containerd.sock\n19.259  runc             220843 220817   0 \n19.269  exe              220851 220843   0 /proc/self/exe init\n19.284  build-script-bu  220854 219802   0 /target/debug/build/clang-sys-6f971d4cb8e593f1/build-script-build\n19.307  cc               220856 220687   0 /tmp/native-trace-219629-1783993297970/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcbcLKmO/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.0dw1tw7.rcgu.o ...\n19.310  cc               220884 220856   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcbcLKmO/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.0dw1tw7.rcgu.o ...\n19.321  build-script-bu  220870 219802   0 /target/debug/build/bindgen-443da4bed0c44742/build-script-build\n19.327  collect2         220890 220884   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.330  ld.lld           220894 220890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n19.332  rust-lld         220894 220890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.341  exe              220898 220843   0 /proc/1599/exe -exec-root=/var/run/docker 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 d7da31e8f8e1\n19.389  exe              220935 1599     0 /proc/self/exe /var/run/docker/netns/ad1bde85bf61 all false\n19.432  cc               220960 220768   0 /tmp/native-trace-219637-1783993297999/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcVPA5JJ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1xesmss.rcgu.o ...\n19.439  cc               220965 220960   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcVPA5JJ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1xesmss.rcgu.o ...\n19.449  cc               220966 220422   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcy9ee2d/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.453  collect2         220967 220965   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.456  cc               220968 220966   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcy9ee2d/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.462  ld.lld           220969 220967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n19.467  collect2         220970 220968   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.468  rust-lld         220969 220967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.476  ld.lld           220971 220970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n19.481  rust-lld         220971 220970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.497  rustc            220976 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.549  runc             221020 220817   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cd --log-format json --systemd-cgroup start 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4\n19.558  sh               220858 220817   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.562  cargo            221026 220858   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.574  build-script-bu  221029 219981   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n19.587  rustc            221030 221029   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.587  cargo-native-tr  221026 220858   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.604  build-script-bu  221034 220337   0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n19.607  rustc            221035 221029   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.615  cargo            221031 221026   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.619  rustc            221036 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.622  build-script-bu  221039 220337   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n19.628  rustc            221042 221039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.636  rustc            221044 221031   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.637  rustc            221045 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span.rs --target x86_64-unknown-linux-gnu\n19.681  rustc            221052 221031   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.700  build-script-bu  221058 220039   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n19.743  rustc            221069 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.749  execsnoop        221074 221026   0 /usr/local/bin/execsnoop -t\n19.752  rustc            221072 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_version --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=96eceed59e2d94f2 ...\n19.754  python3          221074 221026   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.761  rustc            221073 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n19.770  rustc            221059 221058   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.789  runc             221087 214159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda --log-format json --systemd-cgroup kill --all 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7 9\n19.807  sh               221097 2147557   0 /bin/sh -c which ps\n19.809  which            221097 2147557   0 /usr/bin/which ps\n19.811  rustc            221098 221058   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.812  sh               221099 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.814  runc             221101 214159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda --log-format json --systemd-cgroup delete 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7\n19.814  ps               221099 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.858  sh               221110 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.860  cpuUsage.sh      221110 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.862  sed              221112 221110   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.866  cat              221114 221110   0 /usr/bin/cat /proc/2240539/stat\n19.868  cat              221115 221110   0 /usr/bin/cat /proc/4193716/stat\n19.870  sleep            221117 221110   0 /usr/bin/sleep 1\n19.877  rustc            221113 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n19.913  runc             221124 214126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 --log-format json --systemd-cgroup kill --all e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7 9\n19.943  rustc            221134 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.949  runc             221135 214126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 --log-format json --systemd-cgroup delete e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7\n19.980  rustc            221142 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n19.985  rustc            221148 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.043  rustc            221167 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.047  containerd-shim  221168 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda delete\n20.051  runc             221175 221168   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b --log-format json delete --force 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7\n20.059  rustc            221162 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.082  runc             221184 214091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc9 --log-format json --systemd-cgroup kill --all 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0 9\n20.115  runc             221200 214091   0 \n20.127  systemd-sysctl   221206 220753   0 \n20.203  containerd-shim  221217 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 delete\n20.206  runc             221224 221217   0 \n20.272  systemd-sysctl   221239 220753   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0fd9938 --prefix=/net/ipv4/neigh/veth0fd9938 --prefix=/net/ipv6/conf/veth0fd9938 --prefix=/net/ipv6/neigh/veth0fd9938\n20.289  rustc            221238 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.101/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.332  rustc            221246 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_10_0\" --cfg feature=\"clang_11_0\" --cfg feature=\"clang_3_5\" ...\n20.396  containerd-shim  221257 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc9 delete\n20.401  runc             221265 221257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe --log-format json delete --force 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0\n20.443  systemd-sysctl   221270 220753   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda62a9d --prefix=/net/ipv4/neigh/vethda62a9d --prefix=/net/ipv6/conf/vethda62a9d --prefix=/net/ipv6/neigh/vethda62a9d\n20.467  rustc            221274 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.582  rustc            221282 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n20.716  rustc            221292 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.830  rustc            221305 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"meta\" --cfg feature=\"nfa-pikevm\" ...\n20.873  sed              221315 221110   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.876  cat              221320 221110   0 /usr/bin/cat /proc/2240539/stat\n20.879  cat              221327 221110   0 /usr/bin/cat /proc/4193716/stat\n21.053  rustc            221371 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n21.060  cc               221372 221282   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcll75QQ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1bjs2ud.rcgu.o ...\n21.066  cc               221375 221372   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcll75QQ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1bjs2ud.rcgu.o ...\n21.076  collect2         221377 221375   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.083  ld.lld           221378 221377   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n21.090  rust-lld         221378 221377   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.305  build-script-bu  221413 220337   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n21.308  rustc            221415 221413   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.334  rustc            221418 221413   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.380  git              221423 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n21.406  rustc            221426 217491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg feature=\"generate\" ...\n21.666  rustc            221463 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n21.721  cc               221493 221426   0 /tmp/native-trace-217120-1783993291306/shims/cc -m64 /target/debug/build/onig_sys-59f907ac8401f24a/rustcuo3nLW/symbols.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.030y3wwpmxpslzwi3m4ydm7x2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0al51i56e137z2kc5nunukczm.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0b5cu7jowlr0y0g4vwd8a9ci2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0c6h82rfesfc1gt8k7r6g0oqw.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0zogmtdguj4hicd36oif1ytxl.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1qnuft0824tf4ewdv94bwwtnz.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1wwx7oapljv9fqq4vvrg9frny.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.20ivuadoo7yyr8ei8pcvs1yqh.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.31b2vd9gg954cucaewcf2wg10.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3l6vwlgugy6qvjeui7spv41i4.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3n0h4vamwi4srwxgjgnhxqmjg.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3xif1qzcna4xix4e6pbldgf11.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.47geen3afhfg3rd67znzzmctb.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.52jbyqkp68dmb0rynnrhxn2di.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.59pn9ay3ijnoei2ryqr82p6v7.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5hr32dodhdwpscme98twstapn.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5ijw18l8o8m2qyr95vy6xnoav.00ydreg.rcgu.o ...\n21.722  cc               221495 221493   0 /usr/bin/cc -m64 /target/debug/build/onig_sys-59f907ac8401f24a/rustcuo3nLW/symbols.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.030y3wwpmxpslzwi3m4ydm7x2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0al51i56e137z2kc5nunukczm.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0b5cu7jowlr0y0g4vwd8a9ci2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0c6h82rfesfc1gt8k7r6g0oqw.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0zogmtdguj4hicd36oif1ytxl.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1qnuft0824tf4ewdv94bwwtnz.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1wwx7oapljv9fqq4vvrg9frny.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.20ivuadoo7yyr8ei8pcvs1yqh.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.31b2vd9gg954cucaewcf2wg10.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3l6vwlgugy6qvjeui7spv41i4.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3n0h4vamwi4srwxgjgnhxqmjg.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3xif1qzcna4xix4e6pbldgf11.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.47geen3afhfg3rd67znzzmctb.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.52jbyqkp68dmb0rynnrhxn2di.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.59pn9ay3ijnoei2ryqr82p6v7.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5hr32dodhdwpscme98twstapn.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5ijw18l8o8m2qyr95vy6xnoav.00ydreg.rcgu.o ...\n21.731  collect2         221497 221495   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.733  ld.lld           221498 221497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a ...\n21.736  rust-lld         221498 221497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.839  rustc            221527 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n22.082  rustc            221555 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cexpr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2e529dc214fd3c63 ...\n"
}
```

#### Record 22

```json
{
  "argv": [
    "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214459,
  "build_script_target_dir": "chrono-tz-b85d549251c55a98",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build",
  "pid": 214459,
  "ppid": 214402,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "_build_script_out_dir": "/target/debug/build/chrono-tz-b85d549251c55a98/out"
}
```

#### Record 23

```json
{
  "argv": [
    "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build",
  "pid": 214594,
  "ppid": 214402,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out"
}
```

#### Record 24

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214595,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 25

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214601,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214623,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214638,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214652,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe4",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214684,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "argv": [
    "/bin/rustc",
    "--crate-name",
    "probe5",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/bin/rustc",
  "pid": 214716,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 31

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe6",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214736,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 32

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe7",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214760,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe8",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214810,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_build_script_out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "crate": "chrono-tz",
  "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "event_id": "bsrun:f9ad6565f976110f:8e2d527cc78f4889:1df387e90cd124c1",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
  "out_dir": "/target/debug/build/chrono-tz-b85d549251c55a98/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
  "success": true,
  "target": null,
  "version": "0.10.4",
  "_owner": {
    "crate": "chrono-tz",
    "version": "0.10.4",
    "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
    "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
    "source": "cwd_prefix"
  }
}
```

#### Record 35

```json
{
  "crate": "num-traits",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "event_id": "bsrun:f7637966bf5a191e:489dce6f936518b7:bdeb13c681972d74",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
  "out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
  "success": true,
  "target": null,
  "version": "0.2.18",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.18",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
    "source": "cwd_prefix"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214595,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 37

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214601,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 38

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214623,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 39

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214638,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 40

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214652,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 41

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe4",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214684,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 42

```json
{
  "argv": [
    "/bin/rustc",
    "--crate-name",
    "probe5",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/bin/rustc",
  "pid": 214716,
  "ppid": 214594,
  "root_cargo_pid": 214402,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 43

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe6",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214736,
  "ppid": 214594,
  "root_cargo_pid": 214402,
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
    "--crate-name",
    "probe7",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214760,
  "ppid": 214594,
  "root_cargo_pid": 214402,
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
    "--crate-name",
    "probe8",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 214594,
  "build_script_target_dir": "num-traits-8cdeb73dca624620",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 214810,
  "ppid": 214594,
  "root_cargo_pid": 214402,
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
  "time": "2026-07-14T01:41:46.203865+00:00",
  "crate": "chrono-tz",
  "version": "0.10.4",
  "architecture": "ppc64le",
  "duration_seconds": 29.957836974412203,
  "trace_record_count": 35,
  "trace_owner_summary": {
    "owner_package_count": 21,
    "owner_packages": [
      {
        "crate": "chrono-tz-build",
        "version": "0.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono-tz-build@0.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0/Cargo.toml"
      },
      {
        "crate": "parse-zoneinfo",
        "version": "0.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parse-zoneinfo@0.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1/Cargo.toml"
      },
      {
        "crate": "phf_generator",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.12.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.197",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.197",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "phf_codegen",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.12.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.80",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.80",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80/Cargo.toml"
      },
      {
        "crate": "serde_test",
        "version": "1.0.176",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.176",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18/Cargo.toml"
      },
      {
        "crate": "phf_shared",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.12.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1/Cargo.toml"
      },
      {
        "crate": "byteorder",
        "version": "1.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/Cargo.toml"
      },
      {
        "crate": "siphasher",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@1.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0/Cargo.toml"
      },
      {
        "crate": "chrono",
        "version": "0.4.38",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono@0.4.38",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.197",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.197",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.36",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.36",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/Cargo.toml"
      },
      {
        "crate": "tzfile",
        "version": "0.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tzfile@0.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3/Cargo.toml"
      },
      {
        "crate": "phf",
        "version": "0.12.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.12.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.59",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.59",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59/Cargo.toml"
      },
      {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "manifest_path": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4/Cargo.toml"
      }
    ],
    "attributed_event_count": 21,
    "unattributed_event_count": 14,
    "owners": [
      {
        "crate": "chrono-tz",
        "version": "0.10.4",
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
        "crate": "num-traits",
        "version": "0.2.18",
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
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.2.0",
          "name": "autocfg",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#byteorder@1.5.0",
          "name": "byteorder",
          "version": "1.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/byteorder-1.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono@0.4.38",
          "name": "chrono",
          "version": "0.4.38",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.38"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
          "name": "chrono-tz",
          "version": "0.10.4",
          "manifest_path": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#chrono-tz-build@0.5.0",
          "name": "chrono-tz-build",
          "version": "0.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-tz-build-0.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.3.0",
          "name": "fastrand",
          "version": "2.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
          "name": "num-traits",
          "version": "0.2.18",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parse-zoneinfo@0.4.1",
          "name": "parse-zoneinfo",
          "version": "0.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parse-zoneinfo-0.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf@0.12.1",
          "name": "phf",
          "version": "0.12.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_codegen@0.12.1",
          "name": "phf_codegen",
          "version": "0.12.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_codegen-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_generator@0.12.1",
          "name": "phf_generator",
          "version": "0.12.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_generator-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#phf_shared@0.12.1",
          "name": "phf_shared",
          "version": "0.12.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/phf_shared-0.12.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.80",
          "name": "proc-macro2",
          "version": "1.0.80",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.80"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.36",
          "name": "quote",
          "version": "1.0.36",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.36"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.197",
          "name": "serde",
          "version": "1.0.197",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.197"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.197",
          "name": "serde_derive",
          "version": "1.0.197",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.197"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_test@1.0.176",
          "name": "serde_test",
          "version": "1.0.176",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_test-1.0.176"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#siphasher@1.0.1",
          "name": "siphasher",
          "version": "1.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/siphasher-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.59",
          "name": "syn",
          "version": "2.0.59",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.59"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tzfile@0.1.3",
          "name": "tzfile",
          "version": "0.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tzfile-0.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
        }
      ],
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 214430,
      "ppid": 214413,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:f67ce77a0926d025:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
      "pid": 214430,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:f5e03c3f97148e18:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "3f44b34747f774ee92e42e8f7301cdc3565cfbfc588f6db011b4fde595173b61",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:f625bd3e1908f78f:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "7625074197c276019039eecf31d735aa3711a27edfd00ef8cf5538bc21927f43",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:fd40ce395de1dd62:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "b92faa7eb749e24c3da632116d76011b554ce9007f70ff723f571d4f019c3dfc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:9be3628c25293c37:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "bb1344f8d97806df77b268553c11d91458a2d8818e0941e53a3f99d0c3666b2b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:b7b7de4a39a4d7f6:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "ab52ec4323aed1b3bf0c126a64d4f755108bd9ee178dcb88d8978263385b9f60",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "used:cc:6bde491006586088:308daaf46ee0e957:bf58ef438fa3a928",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
      "pid": 214430,
      "sha256": "e9bfdebd4a0234a4f19dc176c8fb0fb8e3dfabeb49b6dd86470fa9c980077c2d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
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
      "output": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "cargo_pkg_name": "chrono-tz",
      "cargo_pkg_version": "0.10.4",
      "context_path": "/tmp/native-trace-214195-1783993281403/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-214195-1783993281403/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 214430,
      "ppid": 214413,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
        "/target/debug/build/chrono-tz-b85d549251c55a98",
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
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/rustcbpFqBc/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3ktuefat30q1ij4du97khh56g.10fl3fz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.3u2zlwas68ajhwbgnbwu7xk8s.10fl3fz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.64kflrbn46njo2ve4l946lu9o.10fl3fz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.892jt8fc7sk1e8i8qm8ylht5s.10fl3fz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.eys9a77qrau8sjs5l9ywby2ed.10fl3fz.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/chrono-tz-b85d549251c55a98",
          "kind": "object",
          "path": "/target/debug/build/chrono-tz-b85d549251c55a98/build_script_build-b85d549251c55a98.emmtm7oiznwsv3l09hwwztnkz.10fl3fz.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-214430-1783993283618939854.map",
      "pid": 214430,
      "ppid": 214413,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-214430-1783993283618939854.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "exit_code": 0,
      "kind": "exec",
      "pid": 214537,
      "ppid": 214509,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.18",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "event_id": "used:cc:868aabdfedc436c3:0f1e867ebeba8374:b661e894909a6a6d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
      "pid": 214537,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.18",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "event_id": "used:cc:868aabdfedc436c3:524d55c71fe107ba:b661e894909a6a6d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
      "pid": 214537,
      "sha256": "ec603eb0c38b936a4ba9e6c49956563f3e660063e4622556671851ced3368567",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.18",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "event_id": "used:cc:868aabdfedc436c3:028b9b8a57be3eb5:b661e894909a6a6d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
      "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
      "pid": 214537,
      "sha256": "ad363273c99273de7263901d7ea523c0bc64892a00470e1f1795e9bd17ff9031",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
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
      "output": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.18",
      "context_path": "/tmp/native-trace-214195-1783993281403/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-214195-1783993281403/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 214537,
      "ppid": 214509,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y",
        "/target/debug/build/num-traits-8cdeb73dca624620",
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
          "directory": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y",
          "kind": "object",
          "path": "/target/debug/build/num-traits-8cdeb73dca624620/rustcm5oH1Y/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-8cdeb73dca624620",
          "kind": "object",
          "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.build_script_build.920d4d27b807415b-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-8cdeb73dca624620",
          "kind": "object",
          "path": "/target/debug/build/num-traits-8cdeb73dca624620/build_script_build-8cdeb73dca624620.3iygy8vh24kdtlepju8ouy98g.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-e07444c6eac50af5.rlib(autocfg-e07444c6eac50af5.autocfg.c50089c9b4c5cbb2-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-214537-1783993283866220799.map",
      "pid": 214537,
      "ppid": 214509,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-214537-1783993283866220799.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
      "parsed_event_count": 1191,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1192,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n18.805  runc             220579 220568   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d99b48bf02e028923c1160684581df1a74f8a69b2a235ebba1604f12060119b --log-format json delete --force d99b48bf02e028923c1160684581df1a74f8a69b2a235ebba1604f12060119be\n18.820  runc             220593 1599     0 /usr/bin/runc --version\n18.827  docker-init      220602 1599     0 /usr/bin/docker-init --version\n18.830  docker           220603 220315   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.842  containerd-shim  220611 1663     0 \n18.842  runc             220621 220611   0 \n18.851  runc             220631 1599     0 \n18.857  docker-init      220638 1599     0 /usr/bin/docker-init --version\n18.876  rustc            220640 220433   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n18.878  systemd-sysctl   220641 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb9540d3 --prefix=/net/ipv4/neigh/vethb9540d3 --prefix=/net/ipv6/conf/vethb9540d3 --prefix=/net/ipv6/neigh/vethb9540d3\n18.895  rustup           220646 220315   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.906  rustup           220655 220315   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.921  rustc            220665 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n18.946  systemd-sysctl   220670 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha8a8f52 --prefix=/net/ipv4/neigh/vetha8a8f52 --prefix=/net/ipv6/conf/vetha8a8f52 --prefix=/net/ipv6/neigh/vetha8a8f52\n18.948  rustup           220675 220315   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.986  uname            220688 220315   0 /usr/bin/uname -r\n19.014  cc               220689 220221   0 /tmp/native-trace-219340-1783993297394/shims/cc -m64 /target/debug/build/clang-sys-6f971d4cb8e593f1/rustcLYI9CM/symbols.o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.build_script_build.e1f45aacd1af39e3-cgu.0.rcg /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.44ovr9ku5hu9qhasl4b0t7d4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libglob-a91c897b77dd6906.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.015  cc               220691 220689   0 /usr/bin/cc -m64 /target/debug/build/clang-sys-6f971d4cb8e593f1/rustcLYI9CM/symbols.o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.build_script_build.e1f45aacd1af39e3-cgu.0.rcg /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1.44ovr9ku5hu9qhasl4b0t7d4q.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libglob-a91c897b77dd6906.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.023  rustc            220687 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.027  collect2         220696 220691   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.029  rustc            220695 218062   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bindgen --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bindgen-0.71.1/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"logging\" --cfg feature=\"prettyplease\" ...\n19.032  ld.lld           220697 220696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/clang-sys-6f971d4cb8e593f1/build_script_build-6f971d4cb8e593f1 ...\n19.037  rust-lld         220697 220696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc5ZqpSQ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.046  docker           220705 220315   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n19.133  systemd-sysctl   220738 220632   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7a589f5 --prefix=/net/ipv4/neigh/veth7a589f5 --prefix=/net/ipv6/conf/veth7a589f5 --prefix=/net/ipv6/neigh/veth7a589f5\n19.134  systemd-sysctl   220739 220642   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf0c1b76 --prefix=/net/ipv4/neigh/vethf0c1b76 --prefix=/net/ipv6/conf/vethf0c1b76 --prefix=/net/ipv6/neigh/vethf0c1b76\n19.204  containerd-shim  220779 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 start\n19.205  rustc            220768 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n19.222  cc               220776 220402   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcjX4ByY/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.224  cc               220802 220776   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-3d1201f1e2c08588/rustcjX4ByY/symbols.o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.0.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.build_script_build.a9fda21e79ad91d5-cgu.1.r /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588.dc7m7vc1mbu9xvc9yl3f0a4qj.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n19.233  collect2         220810 220802   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.235  ld.lld           220818 220810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n19.250  rust-lld         220818 220810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccuj1AGh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.253  containerd-shim  220817 220779   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 -address /var/run/docker/containerd/containerd.sock\n19.259  runc             220843 220817   0 \n19.269  exe              220851 220843   0 /proc/self/exe init\n19.284  build-script-bu  220854 219802   0 /target/debug/build/clang-sys-6f971d4cb8e593f1/build-script-build\n19.307  cc               220856 220687   0 /tmp/native-trace-219629-1783993297970/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcbcLKmO/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.0dw1tw7.rcgu.o ...\n19.310  cc               220884 220856   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcbcLKmO/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.0dw1tw7.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.0dw1tw7.rcgu.o ...\n19.321  build-script-bu  220870 219802   0 /target/debug/build/bindgen-443da4bed0c44742/build-script-build\n19.327  collect2         220890 220884   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.330  ld.lld           220894 220890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n19.332  rust-lld         220894 220890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3k3JAq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.341  exe              220898 220843   0 /proc/1599/exe -exec-root=/var/run/docker 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4 d7da31e8f8e1\n19.389  exe              220935 1599     0 /proc/self/exe /var/run/docker/netns/ad1bde85bf61 all false\n19.432  cc               220960 220768   0 /tmp/native-trace-219637-1783993297999/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcVPA5JJ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1xesmss.rcgu.o ...\n19.439  cc               220965 220960   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcVPA5JJ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1xesmss.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1xesmss.rcgu.o ...\n19.449  cc               220966 220422   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcy9ee2d/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.453  collect2         220967 220965   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.456  cc               220968 220966   0 /usr/bin/cc -m64 /target/debug/build/quote-c09a40bfdaa87378/rustcy9ee2d/symbols.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.build_script_build.cfc6688302646823-cgu.0.rcgu.o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378.d3pt34yu76rtdvpm2gzziau7k.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n19.462  ld.lld           220969 220967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n19.467  collect2         220970 220968   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n19.468  rust-lld         220969 220967   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccVJPTPy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.476  ld.lld           220971 220970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n19.481  rust-lld         220971 220970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cctEINN7.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n19.497  rustc            220976 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.549  runc             221020 220817   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cd --log-format json --systemd-cgroup start 3a32af709c4a8e7ad95fc72f0617e5469861e6e460423e6cbe04e2224cdcc7b4\n19.558  sh               220858 220817   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n19.562  cargo            221026 220858   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n19.574  build-script-bu  221029 219981   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n19.587  rustc            221030 221029   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.587  cargo-native-tr  221026 220858   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n19.604  build-script-bu  221034 220337   0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n19.607  rustc            221035 221029   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.615  cargo            221031 221026   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n19.619  rustc            221036 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.622  build-script-bu  221039 220337   0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n19.628  rustc            221042 221039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n19.636  rustc            221044 221031   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.637  rustc            221045 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span.rs --target x86_64-unknown-linux-gnu\n19.681  rustc            221052 221031   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n19.700  build-script-bu  221058 220039   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n19.743  rustc            221069 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n19.749  execsnoop        221074 221026   0 /usr/local/bin/execsnoop -t\n19.752  rustc            221072 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rustc_version --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc_version-0.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=96eceed59e2d94f2 ...\n19.754  python3          221074 221026   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n19.761  rustc            221073 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.40/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) ...\n19.770  rustc            221059 221058   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.789  runc             221087 214159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda --log-format json --systemd-cgroup kill --all 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7 9\n19.807  sh               221097 2147557   0 /bin/sh -c which ps\n19.809  which            221097 2147557   0 /usr/bin/which ps\n19.811  rustc            221098 221058   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n19.812  sh               221099 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.814  runc             221101 214159   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda --log-format json --systemd-cgroup delete 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7\n19.814  ps               221099 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n19.858  sh               221110 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n19.860  cpuUsage.sh      221110 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n19.862  sed              221112 221110   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.866  cat              221114 221110   0 /usr/bin/cat /proc/2240539/stat\n19.868  cat              221115 221110   0 /usr/bin/cat /proc/4193716/stat\n19.870  sleep            221117 221110   0 /usr/bin/sleep 1\n19.877  rustc            221113 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_location.rs --target x86_64-unknown-linux-gnu\n19.913  runc             221124 214126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 --log-format json --systemd-cgroup kill --all e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7 9\n19.943  rustc            221134 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n19.949  runc             221135 214126   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 --log-format json --systemd-cgroup delete e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7\n19.980  rustc            221142 221034   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/debug/build/proc-macro2-11305a21490ecd1d/out/probe src/probe/proc_macro_span_file.rs --target x86_64-unknown-linux-gnu\n19.985  rustc            221148 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.043  rustc            221167 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.047  containerd-shim  221168 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfda delete\n20.051  runc             221175 221168   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b --log-format json delete --force 097c26c705a8843f8553f4886900beefab47070b27cae4b6236f953bfdae49b7\n20.059  rustc            221162 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.082  runc             221184 214091   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc9 --log-format json --systemd-cgroup kill --all 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0 9\n20.115  runc             221200 214091   0 \n20.127  systemd-sysctl   221206 220753   0 \n20.203  containerd-shim  221217 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082727d7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/e0366aa99da75ee433a89e8d4a06a7c4d956c2ebb86ef0aca43eb260082 delete\n20.206  runc             221224 221217   0 \n20.272  systemd-sysctl   221239 220753   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0fd9938 --prefix=/net/ipv4/neigh/veth0fd9938 --prefix=/net/ipv6/conf/veth0fd9938 --prefix=/net/ipv6/neigh/veth0fd9938\n20.289  rustc            221238 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.101/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.332  rustc            221246 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name clang_sys --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clang-sys-1.8.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clang_10_0\" --cfg feature=\"clang_11_0\" --cfg feature=\"clang_3_5\" ...\n20.396  containerd-shim  221257 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc9 delete\n20.401  runc             221265 221257   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe --log-format json delete --force 6969e01d4136c8d649415143d3a0a4ed5ef437bb22295b13a5b337d3cc986fe0\n20.443  systemd-sysctl   221270 220753   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethda62a9d --prefix=/net/ipv4/neigh/vethda62a9d --prefix=/net/ipv6/conf/vethda62a9d --prefix=/net/ipv6/neigh/vethda62a9d\n20.467  rustc            221274 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n20.582  rustc            221282 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"async-timeout\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n20.716  rustc            221292 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n20.830  rustc            221305 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"meta\" --cfg feature=\"nfa-pikevm\" ...\n20.873  sed              221315 221110   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n20.876  cat              221320 221110   0 /usr/bin/cat /proc/2240539/stat\n20.879  cat              221327 221110   0 /usr/bin/cat /proc/4193716/stat\n21.053  rustc            221371 220337   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n21.060  cc               221372 221282   0 /tmp/native-trace-219521-1783993297731/shims/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcll75QQ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1bjs2ud.rcgu.o ...\n21.066  cc               221375 221372   0 /usr/bin/cc -m64 /target/debug/build/rstest_macros-21683396f349e724/rustcll75QQ/symbols.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0d9q06lf0l4dgn1z56ih6vm47.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.0e4n50karu9hnkfcjauwkw87r.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.22s4pu98ifnjm2juclgcod34t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.29mp8u7knhkgaybgojm0e0xpa.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2w9sxabyrb7w7n7kndm9i6qjm.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.2zssryagiddnfaqdbj84zipud.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.32tthdlenw5vwxcu9g84z210g.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3aclwjrv080qjwci6hlqjhxis.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3cr7tasob24k79j38eayhezoq.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.3dnpbhmvrct5qg9oshioxkwed.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.409tccqius696oeybm5esdm2t.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.4i2xh5dvcc3mrfwkjqc9n193v.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5dc4gzryzgft4cfqpzchghsbj.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.5iwspyyu8j9agd7qwd7fc0umy.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.68l3y3ug7pcgde8d02s05vqgg.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.6nzwhuvbuo5kk0fg2andb9c80.1bjs2ud.rcgu.o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724.7wv9ry5cax6tuzhaeth6rvfbd.1bjs2ud.rcgu.o ...\n21.076  collect2         221377 221375   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.083  ld.lld           221378 221377   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rstest_macros-21683396f349e724/build_script_build-21683396f349e724 ...\n21.090  rust-lld         221378 221377   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYHqiOF.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.305  build-script-bu  221413 220337   0 /target/debug/build/rstest_macros-21683396f349e724/build-script-build\n21.308  rustc            221415 221413   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.334  rustc            221418 221413   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n21.380  git              221423 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n21.406  rustc            221426 217491   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bindgen\" --cfg feature=\"default\" --cfg feature=\"generate\" ...\n21.666  rustc            221463 219981   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n21.721  cc               221493 221426   0 /tmp/native-trace-217120-1783993291306/shims/cc -m64 /target/debug/build/onig_sys-59f907ac8401f24a/rustcuo3nLW/symbols.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.030y3wwpmxpslzwi3m4ydm7x2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0al51i56e137z2kc5nunukczm.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0b5cu7jowlr0y0g4vwd8a9ci2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0c6h82rfesfc1gt8k7r6g0oqw.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0zogmtdguj4hicd36oif1ytxl.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1qnuft0824tf4ewdv94bwwtnz.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1wwx7oapljv9fqq4vvrg9frny.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.20ivuadoo7yyr8ei8pcvs1yqh.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.31b2vd9gg954cucaewcf2wg10.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3l6vwlgugy6qvjeui7spv41i4.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3n0h4vamwi4srwxgjgnhxqmjg.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3xif1qzcna4xix4e6pbldgf11.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.47geen3afhfg3rd67znzzmctb.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.52jbyqkp68dmb0rynnrhxn2di.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.59pn9ay3ijnoei2ryqr82p6v7.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5hr32dodhdwpscme98twstapn.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5ijw18l8o8m2qyr95vy6xnoav.00ydreg.rcgu.o ...\n21.722  cc               221495 221493   0 /usr/bin/cc -m64 /target/debug/build/onig_sys-59f907ac8401f24a/rustcuo3nLW/symbols.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.030y3wwpmxpslzwi3m4ydm7x2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0al51i56e137z2kc5nunukczm.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0b5cu7jowlr0y0g4vwd8a9ci2.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0c6h82rfesfc1gt8k7r6g0oqw.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.0zogmtdguj4hicd36oif1ytxl.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1qnuft0824tf4ewdv94bwwtnz.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.1wwx7oapljv9fqq4vvrg9frny.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.20ivuadoo7yyr8ei8pcvs1yqh.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.31b2vd9gg954cucaewcf2wg10.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3l6vwlgugy6qvjeui7spv41i4.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3n0h4vamwi4srwxgjgnhxqmjg.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.3xif1qzcna4xix4e6pbldgf11.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.47geen3afhfg3rd67znzzmctb.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.52jbyqkp68dmb0rynnrhxn2di.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.59pn9ay3ijnoei2ryqr82p6v7.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5hr32dodhdwpscme98twstapn.00ydreg.rcgu.o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a.5ijw18l8o8m2qyr95vy6xnoav.00ydreg.rcgu.o ...\n21.731  collect2         221497 221495   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n21.733  ld.lld           221498 221497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/onig_sys-59f907ac8401f24a/build_script_build-59f907ac8401f24a ...\n21.736  rust-lld         221498 221497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccc9z96C.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n21.839  rustc            221527 220039   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n22.082  rustc            221555 219802   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cexpr --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cexpr-0.6.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=2e529dc214fd3c63 ...\n"
    },
    {
      "argv": [
        "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214459,
      "build_script_target_dir": "chrono-tz-b85d549251c55a98",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build",
      "pid": 214459,
      "ppid": 214402,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build",
      "pid": 214594,
      "ppid": 214402,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214595,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214601,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214623,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe2",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214638,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe3",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214652,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe4",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214684,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/bin/rustc",
        "--crate-name",
        "probe5",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/bin/rustc",
      "pid": 214716,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe6",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214736,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe7",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214760,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe8",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214810,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "chrono-tz",
      "cwd": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "event_id": "bsrun:f9ad6565f976110f:8e2d527cc78f4889:1df387e90cd124c1",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/chrono-tz-b85d549251c55a98/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
      "out_dir": "/target/debug/build/chrono-tz-b85d549251c55a98/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
      "success": true,
      "target": null,
      "version": "0.10.4",
      "_owner": {
        "crate": "chrono-tz",
        "version": "0.10.4",
        "package_id": "path+file:///tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4#chrono-tz@0.10.4",
        "manifest_dir": "/tmp/crate-build-ppc64le-qkh43822/src/chrono-tz-0.10.4",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "num-traits",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "event_id": "bsrun:f7637966bf5a191e:489dce6f936518b7:bdeb13c681972d74",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/num-traits-8cdeb73dca624620/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
      "out_dir": "/target/debug/build/num-traits-8cdeb73dca624620/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
      "success": true,
      "target": null,
      "version": "0.2.18",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.18",
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
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214595,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214601,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214623,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe2",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214638,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe3",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214652,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe4",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214684,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/bin/rustc",
        "--crate-name",
        "probe5",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/bin/rustc",
      "pid": 214716,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe6",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214736,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe7",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214760,
      "ppid": 214594,
      "root_cargo_pid": 214402,
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
        "probe8",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-129985941edfd20c/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 214594,
      "build_script_target_dir": "num-traits-8cdeb73dca624620",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 214810,
      "ppid": 214594,
      "root_cargo_pid": 214402,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1020,
    "crate": "chrono-tz",
    "version": "0.10.4",
    "crate_id": "6788",
    "version_id": "1637778",
    "downloads": 20455435,
    "cumulative_downloads": 89863114821,
    "cumulative_share_of_global": 0.3359774408930932,
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
