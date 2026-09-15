# `rustfft` `6.2.0`

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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
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
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
    "/target/debug/build/rustfft-df5ef03d367a47e7",
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
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-554203-1783994761424653306.map",
  "pid": 554203,
  "ppid": 554143,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-554203-1783994761424653306.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
      "name": "autocfg",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
      "name": "bumpalo",
      "version": "3.14.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_error_panic_hook@0.1.7",
      "name": "console_error_panic_hook",
      "version": "0.1.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.8",
      "name": "getrandom",
      "version": "0.2.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.67",
      "name": "js-sys",
      "version": "0.3.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.140",
      "name": "libc",
      "version": "0.2.140",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
      "name": "log",
      "version": "0.4.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-complex@0.4.3",
      "name": "num-complex",
      "version": "0.4.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
      "name": "num-integer",
      "version": "0.1.45",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
      "name": "num-traits",
      "version": "0.2.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
      "name": "once_cell",
      "version": "1.19.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#paste@1.0.12",
      "name": "paste",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
      "name": "ppv-lite86",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#primal-check@0.3.3",
      "name": "primal-check",
      "version": "0.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
      "name": "proc-macro2",
      "version": "1.0.78",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
      "name": "quote",
      "version": "1.0.35",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
      "name": "rand",
      "version": "0.8.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
      "name": "rand_chacha",
      "version": "0.3.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
      "name": "rand_core",
      "version": "0.6.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
      "name": "rustfft",
      "version": "6.2.0",
      "manifest_path": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
      "name": "scoped-tls",
      "version": "1.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#strength_reduce@0.2.4",
      "name": "strength_reduce",
      "version": "0.2.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
      "name": "syn",
      "version": "2.0.48",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#transpose@0.2.2",
      "name": "transpose",
      "version": "0.2.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
      "name": "version_check",
      "version": "0.9.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
      "name": "wasi",
      "version": "0.11.0+wasi-snapshot-preview1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.90",
      "name": "wasm-bindgen",
      "version": "0.2.90",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.90",
      "name": "wasm-bindgen-backend",
      "version": "0.2.90",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.40",
      "name": "wasm-bindgen-futures",
      "version": "0.4.40",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.90",
      "name": "wasm-bindgen-macro",
      "version": "0.2.90",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.90",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.90",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.90",
      "name": "wasm-bindgen-shared",
      "version": "0.2.90",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test@0.3.40",
      "name": "wasm-bindgen-test",
      "version": "0.3.40",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test-macro@0.3.40",
      "name": "wasm-bindgen-test-macro",
      "version": "0.3.40",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.67",
      "name": "web-sys",
      "version": "0.3.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67"
    }
  ],
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 554203,
  "ppid": 554143,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:6a0f63771649a8be:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
  "pid": 554203,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:e4a69f4d71ba66e6:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "6437a850e1b787aac4e798558f133afbe0564bc6506044196dc91cfdb4dfbc0a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:14a6c9e2c3add19e:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "a2edf192d21e9907013f8968ae53232ee4a2c249f101143a9a5999dc237800f8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:5f271300f5ecfaf2:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "d833e5af2fe21a1b32965499d18a6ec2a25545bb991ce9674a364851d06160df",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:b0bc125b0b6186fa:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "dc79c8abc1eed44ee061019c51f5fa79ca1a7b8112b4fc1356aca45e548d1cf5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:138bd5ad47ddd299:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "75744d21224121c5ca6d73536367ddac3c7c339488016e42440f8a74fd236082",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:2b7a1d8d359eaa93:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "ad08084d61dc32be1c7f85691e9e973256ceee9cc53dd47ff150b90493a380ea",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:56e9cbb7f0898d7f:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "dad27a1e9400abe51ff173f4683627ed38b079def6099169e68761540e6fdb7c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:a68ebd0239309417:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "8dcc64f78a4b29b0a288f34965f2cde81b7af8465ab483d77eb29dee6acf2f2d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "used:cc:fd90d2709987b7e4:60cec5695b751425:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
  "pid": 554203,
  "sha256": "197f2b51d1e298fd95726267e40617336337134065147c3068f766b3fd604153",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
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
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 554203,
  "ppid": 554143,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
    "/target/debug/build/rustfft-df5ef03d367a47e7",
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
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-554203-1783994761424653306.map",
  "pid": 554203,
  "ppid": 554143,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-554203-1783994761424653306.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "exit_code": 0,
  "kind": "exec",
  "pid": 554230,
  "ppid": 554169,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-integer",
  "cargo_pkg_version": "0.1.45",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "event_id": "used:cc:951da16589636ef0:c5ebf34275ab6627:0525545e6d709c1c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
  "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
  "pid": 554230,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-integer",
  "cargo_pkg_version": "0.1.45",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "event_id": "used:cc:951da16589636ef0:5909e849dfede5f1:0525545e6d709c1c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
  "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
  "pid": 554230,
  "sha256": "abde26479486c8b97136f79e09a61466c5e6af08583141313d53f77b1f36b972",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-integer",
  "cargo_pkg_version": "0.1.45",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "event_id": "used:cc:951da16589636ef0:0ba06bcda6caddf5:0525545e6d709c1c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
  "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
  "pid": 554230,
  "sha256": "0d24f03a096241fd10e919cb74830596c5ba68ee9bc21355d0e60ddf55b3dd53",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
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
  "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "cargo_pkg_name": "num-integer",
  "cargo_pkg_version": "0.1.45",
  "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 554230,
  "ppid": 554169,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
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
      "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA",
      "kind": "object",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
      "kind": "object",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
      "kind": "object",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-554230-1783994761443450627.map",
  "pid": 554230,
  "ppid": 554169,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-554230-1783994761443450627.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "exit_code": 0,
  "kind": "exec",
  "pid": 554229,
  "ppid": 554168,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.15",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "event_id": "used:cc:10dd48d5a331e0dc:cd06019a3355a5a0:817d5ec450636eb3",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
  "path": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
  "pid": 554229,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.15",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "event_id": "used:cc:10dd48d5a331e0dc:1a3540513fe3f338:817d5ec450636eb3",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
  "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
  "pid": 554229,
  "sha256": "19590024724d0923fe431bd0e9dcb4d3e97e1becb0837bbd4d35dae66f73ef07",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.15",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "event_id": "used:cc:10dd48d5a331e0dc:25cb5d4c3f3c317c:817d5ec450636eb3",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
  "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
  "pid": 554229,
  "sha256": "c4e0b005f110a15b1e99b5cce1d8396ca9cd35ca39de74fc2c1aa04f44d7f1de",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
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
  "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.15",
  "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 554229,
  "ppid": 554168,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 29

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd",
    "/target/debug/build/num-traits-381059396003c1df",
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
      "directory": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd",
      "kind": "object",
      "path": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-381059396003c1df",
      "kind": "object",
      "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-381059396003c1df",
      "kind": "object",
      "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-554229-1783994761442042424.map",
  "pid": 554229,
  "ppid": 554168,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-554229-1783994761442042424.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cargo_manifest_dir"
  }
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

#### Record 31

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1343,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1345,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "d5eaa1 ...\n18.147  rustc            559793 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_10\", \"v2_12\", \"v2_14\", \"v2_16\", \"v2_18\", \"v2_20\", \"v2_22\", \"v2_24\", \"v2_26\", \"v2_28\", \"v2_30\", \"v2_32\",  -C metadata=e32b5cbb99549cb2 ...\n18.153  rustc            559783 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=5bf917358a455423 ...\n18.156  rustc            559784 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=2bccf65b8fe5aec7 ...\n18.168  rustc            559795 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=e06e72fa969977d5 ...\n18.170  cargo            559798 558269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.172  rustc            559786 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=7162d9a34f79e387 ...\n18.192  rustc            559796 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) -C metadata=a916acebc876ca5c ...\n18.207  rustup           559817 543883   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.207  rustc            559815 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.255  rustc            559850 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n18.278  rustc            559849 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"mint\", \"rand\", \"serde\", \"swizzle\", \"unstable\")) -C metadata=d5e815ac590d38c1 ...\n18.324  cc               559887 559783   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/atk-sys-f47ee198205ea3f3/rustcJsBuIv/symbols.o /target/debug/build/atk-sys-f47ee198205ea3f3/build_script_build-f47ee198205ea3f3.build_script_build.6b553cd55fd300f5-cgu.0.rcgu. /target/debug/build/atk-sys-f47ee198205ea3f3/build_script_build-f47ee198205ea3f3.5yhyvlw2cek213c8436sxkt0e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.331  cc               559909 559887   0 \n18.348  collect2         559914 559909   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI88GpP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.348  ld.lld           559915 559914   0 \n18.348  rust-lld         559915 559914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI88GpP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.357  cc               559920 559741   0 /tmp/native-trace-558407-1783994775060/shims/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcTPr6aj/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.0ry9q5y.rcgu.o ...\n18.361  cc               559922 559920   0 /usr/bin/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcTPr6aj/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.0ry9q5y.rcgu.o ...\n18.365  collect2         559924 559922   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.368  ld.lld           559925 559924   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3 ...\n18.370  rust-lld         559925 559924   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.374  cc               559921 559789   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gio-sys-41f6433ceda9a0d5/rustc4egNef/symbols.o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.build_script_build.9c3da3e30cad326f-cgu.0.rcgu. /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.albec7xtawunadop6wo7az1t6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.408  cc               559962 559788   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/rustcGMFXS1/symbols.o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.build_script_build.1bf53d0482f122 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.7utbj96wgsp3ll0xkch2aun1h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.408  cc               559968 559962   0 /usr/bin/cc -m64 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/rustcGMFXS1/symbols.o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.build_script_build.1bf53d0482f122 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.7utbj96wgsp3ll0xkch2aun1h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.413  collect2         559970 559968   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.418  ld.lld           559971 559970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef ...\n18.420  cc               559969 559782   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/cairo-sys-rs-ae88d44245f39edc/rustch3GmSw/symbols.o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.build_script_build.dc2856f2b8dd5f42-cgu.0. /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.98vnos2lhvdlr7gy3ubslziu7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.423  rust-lld         559971 559970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.436  cargo            559974 558399   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.439  cc               559975 559969   0 /usr/bin/cc -m64 /target/debug/build/cairo-sys-rs-ae88d44245f39edc/rustch3GmSw/symbols.o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.build_script_build.dc2856f2b8dd5f42-cgu.0. /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.98vnos2lhvdlr7gy3ubslziu7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.445  collect2         559978 559975   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.447  ld.lld           559981 559978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc ...\n18.452  cc               559977 559921   0 /usr/bin/cc -m64 /target/debug/build/gio-sys-41f6433ceda9a0d5/rustc4egNef/symbols.o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.build_script_build.9c3da3e30cad326f-cgu.0.rcgu. /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.albec7xtawunadop6wo7az1t6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.452  rust-lld         559981 559978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.466  collect2         559989 559977   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.475  ld.lld           560000 559989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5 ...\n18.477  rust-lld         560000 559989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.482  rustc            560001 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.496  rustc            560011 558513   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128_support\", \"nightly\")) -C metadata=e7b790f7c7e88113 ...\n18.503  build-script-bu  560031 559715   0 /target/debug/build/cgmath-d9745ec9a83e1cb3/build-script-build\n18.514  cc               560025 559787   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/pango-sys-7efecf5bb9a79701/rustcs5ziyZ/symbols.o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.build_script_build.eff4b66755a69e8f-cgu.0.rcg /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.e93n4i0ez3790mcryu9uaevuk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.527  cc               560077 559765   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/glib-sys-49a54380333624c7/rustcb9cN9D/symbols.o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.build_script_build.92c46b64b0c2d7aa-cgu.0.rcgu /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.9ha3novm5hzziw455s8wcgcry.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.529  cc               560093 560077   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-49a54380333624c7/rustcb9cN9D/symbols.o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.build_script_build.92c46b64b0c2d7aa-cgu.0.rcgu /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.9ha3novm5hzziw455s8wcgcry.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.532  cc               560091 559781   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gdk-sys-ac0b5d633e2bdb61/rustcYzaMfy/symbols.o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.build_script_build.7da4f7b49862835b-cgu.0.rcgu. /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.dz0s08lzzuodtl1o3jr6a513i.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.532  cc               560095 560091   0 /usr/bin/cc -m64 /target/debug/build/gdk-sys-ac0b5d633e2bdb61/rustcYzaMfy/symbols.o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.build_script_build.7da4f7b49862835b-cgu.0.rcgu. /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.dz0s08lzzuodtl1o3jr6a513i.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.538  collect2         560104 560093   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.540  ld.lld           560105 560104   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7 ...\n18.541  rust-lld         560105 560104   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.543  collect2         560106 560095   0 \n18.549  ld.lld           560107 560106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxQz3pX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61 ...\n18.557  rust-lld         560107 560106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxQz3pX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.558  cc               560108 559849   0 /tmp/native-trace-558269-1783994774811/shims/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcumA3so/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.1465ffj.rcgu.o ...\n18.563  cc               560109 560108   0 /usr/bin/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcumA3so/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.1465ffj.rcgu.o ...\n18.565  cc               560114 560025   0 /usr/bin/cc -m64 /target/debug/build/pango-sys-7efecf5bb9a79701/rustcs5ziyZ/symbols.o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.build_script_build.eff4b66755a69e8f-cgu.0.rcg /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.e93n4i0ez3790mcryu9uaevuk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.575  rustc            560121 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=5bf917358a455423 ...\n18.575  rustc            560124 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=2bccf65b8fe5aec7 ...\n18.576  collect2         560123 560109   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.579  ld.lld           560134 560123   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3 ...\n18.580  rustc            560119 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=b6c73f6fbaf20e62 ...\n18.581  rust-lld         560134 560123   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.581  rustc            560132 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=bba6f3e8691efe52 ...\n18.582  rustc            560133 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=7162d9a34f79e387 ...\n18.592  rustc            560136 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cairo-sys-rs-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"freetype\", \"glib\", \"pdf\", \"png\", \"ps\", \"script\", \"svg\", \"use_glib\", \"v1_16\", \"v1_18\", \"win32-surface\", \"win -C metadata=d4233a0aa2d5eaa1 ...\n18.593  collect2         560122 560114   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.598  rustc            560102 558513   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crypto --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"with-bench\")) -C metadata=46585077d76dd543 ...\n18.601  rustc            560127 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=e06e72fa969977d5 ...\n18.609  ld.lld           560164 560122   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701 ...\n18.613  rustc            560144 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.613  rustc            560183 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name vcpkg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/vcpkg-0.2.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=69468eef4ea66cf5 ...\n18.616  cc               560158 559793   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/rustcGKvPdM/symbols.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2k8kbs1rkryvtfacr12ooncqg.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.90ckgnps9ruu1fqleiqxl5bxe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.akwn53nutluvdp20f1xzpmqas.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.aunsk96f9wyur5k7oolfa03je.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dhjob3n77402m3wau53fiahdv.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dn9kexccof6r8ptg9nfy34hfe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2qy2xs7ln0v0m11xspllg458l.14n1pjl.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib ...\n18.619  rust-lld         560164 560122   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.629  cc               560184 560158   0 /usr/bin/cc -m64 /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/rustcGKvPdM/symbols.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2k8kbs1rkryvtfacr12ooncqg.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.90ckgnps9ruu1fqleiqxl5bxe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.akwn53nutluvdp20f1xzpmqas.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.aunsk96f9wyur5k7oolfa03je.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dhjob3n77402m3wau53fiahdv.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dn9kexccof6r8ptg9nfy34hfe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2qy2xs7ln0v0m11xspllg458l.14n1pjl.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib ...\n18.649  cc               560189 559786   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/rustcOUir17/symbols.o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.build_script_build.f02832431664dc17-cgu.0.rcgu. /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.4dzkytt7zrst7bnu5zedry4t4.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.652  cc               560096 559795   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/rustcPsuPWx/symbols.o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.build_script_build.25504bd235bc3179-cgu. /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.28t6hu43ubqewqkd5y2hurn55.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.657  cc               560224 560096   0 /usr/bin/cc -m64 /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/rustcPsuPWx/symbols.o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.build_script_build.25504bd235bc3179-cgu. /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.28t6hu43ubqewqkd5y2hurn55.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.661  rustc            560220 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n18.662  collect2         560225 560224   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.666  ld.lld           560226 560225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499 ...\n18.670  cc               560219 560189   0 /usr/bin/cc -m64 /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/rustcOUir17/symbols.o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.build_script_build.f02832431664dc17-cgu.0.rcgu. /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.4dzkytt7zrst7bnu5zedry4t4.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.672  rust-lld         560226 560225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.689  rustc            560231 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_10\", \"v2_12\", \"v2_14\", \"v2_16\", \"v2_18\", \"v2_20\", \"v2_22\", \"v2_24\", \"v2_26\", \"v2_28\", \"v2_30\", \"v2_32\",  -C metadata=e32b5cbb99549cb2 ...\n18.710  rustc            560135 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) -C metadata=a916acebc876ca5c ...\n18.719  cc               560223 559796   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/soup3-sys-41647c642ee4ea07/rustcuGAAHH/symbols.o /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.build_script_build.4682c6ad9c7646bb-cgu.0.rcg /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.dndse5oijzuyee2zqpbg1965m.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.722  rustc            560253 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/javascriptcore-rs-sys-1.1.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_28\", \"v2_38\")) -C metadata=0de86063c84085c3 ...\n18.727  cc               560264 560223   0 /usr/bin/cc -m64 /target/debug/build/soup3-sys-41647c642ee4ea07/rustcuGAAHH/symbols.o /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.build_script_build.4682c6ad9c7646bb-cgu.0.rcg /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.dndse5oijzuyee2zqpbg1965m.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.731  collect2         560257 560219   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSApDil.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.746  collect2         560199 560184   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.750  rustc            560265 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\")) -C metadata=36447ea903029f40 ...\n18.759  ld.lld           560276 560199   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722 ...\n18.761  build-script-bu  560281 559798   0 /target/debug/build/cgmath-d9745ec9a83e1cb3/build-script-build\n18.764  cc               560269 559784   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gobject-sys-32eddc0241afc4ef/rustc2llJ4Z/symbols.o /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.build_script_build.1670ac7eb87fbcd9-cgu.0.r /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.9iycmgyd8j08udj0zzgiapsqw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.769  ld.lld           560268 560257   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSApDil.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54 ...\n18.773  cc               560291 560269   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-32eddc0241afc4ef/rustc2llJ4Z/symbols.o /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.build_script_build.1670ac7eb87fbcd9-cgu.0.r /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.9iycmgyd8j08udj0zzgiapsqw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.780  rust-lld         560276 560199   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n"
}
```

#### Record 32

```json
{
  "argv": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554344,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
  "pid": 554344,
  "ppid": 553907,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_build_script_out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out"
}
```

#### Record 33

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554344,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554347,
  "ppid": 554344,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_build_script_out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "argv": [
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
  "pid": 554351,
  "ppid": 553907,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out"
}
```

#### Record 35

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554353,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/target/debug/build/num-traits-381059396003c1df/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
  "pid": 554358,
  "ppid": 553907,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out"
}
```

#### Record 37

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554359,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 38

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554370,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554371,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 40

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554392,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_build_script_out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 41

```json
{
  "argv": [
    "/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/bin/rustc",
  "pid": 554393,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 42

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554424,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 43

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554431,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 44

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe4",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554438,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 45

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe5",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554445,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 46

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe6",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554452,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_build_script_out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "crate": "rustfft",
  "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "event_id": "bsrun:49e6d5f006c43d05:ffaac7c3e4ef67e2:e1f030fe76560b4d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
  "out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
  "success": true,
  "target": null,
  "version": "6.2.0",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 48

```json
{
  "crate": "num-integer",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "event_id": "bsrun:5941c1f02bcc48da:e3ea911469aa909d:124bf4a09cbfe4a7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
  "success": true,
  "target": null,
  "version": "0.1.45",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
    "source": "cwd_prefix"
  }
}
```

#### Record 49

```json
{
  "crate": "num-traits",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "event_id": "bsrun:f771365925bccf2d:90a61dfcdcd2850a:d216b3ab71bccee5",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
  "success": true,
  "target": null,
  "version": "0.2.15",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
    "source": "cwd_prefix"
  }
}
```

#### Record 50

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554344,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554347,
  "ppid": 554344,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 51

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554353,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 52

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554359,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 53

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554370,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 54

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554371,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 55

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554351,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554392,
  "ppid": 554351,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 56

```json
{
  "argv": [
    "/bin/rustc",
    "--crate-name",
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/bin/rustc",
  "pid": 554393,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 57

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554424,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 58

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554431,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 59

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe4",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554438,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 60

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe5",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554445,
  "ppid": 554358,
  "root_cargo_pid": 553907,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 61

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe6",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 554358,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 554452,
  "ppid": 554358,
  "root_cargo_pid": 553907,
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
  "time": "2026-07-14T02:06:20.499940+00:00",
  "crate": "rustfft",
  "version": "6.2.0",
  "architecture": "riscv64",
  "duration_seconds": 26.6226043747738,
  "trace_record_count": 49,
  "trace_owner_summary": {
    "owner_package_count": 37,
    "owner_packages": [
      {
        "crate": "wasi",
        "version": "0.11.0+wasi-snapshot-preview1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.90",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.90",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90/Cargo.toml"
      },
      {
        "crate": "console_error_panic_hook",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_error_panic_hook@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-test-macro",
        "version": "0.3.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test-macro@0.3.40",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-backend",
        "version": "0.2.90",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.90",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-futures",
        "version": "0.4.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.40",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.90",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.90",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.90",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.90",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-test",
        "version": "0.3.40",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test@0.3.40",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40/Cargo.toml"
      },
      {
        "crate": "strength_reduce",
        "version": "0.2.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#strength_reduce@0.2.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "version_check",
        "version": "0.9.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.90",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.90",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90/Cargo.toml"
      },
      {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45/Cargo.toml"
      },
      {
        "crate": "primal-check",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#primal-check@0.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.78",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml"
      },
      {
        "crate": "num-complex",
        "version": "0.4.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-complex@0.4.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15/Cargo.toml"
      },
      {
        "crate": "ppv-lite86",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml"
      },
      {
        "crate": "rand_chacha",
        "version": "0.3.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.19.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0/Cargo.toml"
      },
      {
        "crate": "scoped-tls",
        "version": "1.0.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1/Cargo.toml"
      },
      {
        "crate": "getrandom",
        "version": "0.2.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8/Cargo.toml"
      },
      {
        "crate": "rand_core",
        "version": "0.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml"
      },
      {
        "crate": "transpose",
        "version": "0.2.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#transpose@0.2.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.14.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.1.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml"
      },
      {
        "crate": "js-sys",
        "version": "0.3.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.140",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.140",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140/Cargo.toml"
      },
      {
        "crate": "paste",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#paste@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.35",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml"
      },
      {
        "crate": "rand",
        "version": "0.8.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.48",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48/Cargo.toml"
      },
      {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "manifest_path": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 32,
    "unattributed_event_count": 17,
    "owners": [
      {
        "crate": "rustfft",
        "version": "6.2.0",
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
      },
      {
        "crate": "num-integer",
        "version": "0.1.45",
        "event_count": 8,
        "kind_counts": {
          "exec": 1,
          "used_input": 3,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "num-traits",
        "version": "0.2.15",
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
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
          "name": "autocfg",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
          "name": "bumpalo",
          "version": "3.14.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#console_error_panic_hook@0.1.7",
          "name": "console_error_panic_hook",
          "version": "0.1.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console_error_panic_hook-0.1.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#getrandom@0.2.8",
          "name": "getrandom",
          "version": "0.2.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.67",
          "name": "js-sys",
          "version": "0.3.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.140",
          "name": "libc",
          "version": "0.2.140",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.140"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
          "name": "log",
          "version": "0.4.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-complex@0.4.3",
          "name": "num-complex",
          "version": "0.4.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-complex-0.4.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
          "name": "num-integer",
          "version": "0.1.45",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
          "name": "num-traits",
          "version": "0.2.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.19.0",
          "name": "once_cell",
          "version": "1.19.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.19.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#paste@1.0.12",
          "name": "paste",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/paste-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ppv-lite86@0.2.17",
          "name": "ppv-lite86",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ppv-lite86-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#primal-check@0.3.3",
          "name": "primal-check",
          "version": "0.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/primal-check-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.78",
          "name": "proc-macro2",
          "version": "1.0.78",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.78"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.35",
          "name": "quote",
          "version": "1.0.35",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.35"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand@0.8.5",
          "name": "rand",
          "version": "0.8.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.8.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_chacha@0.3.1",
          "name": "rand_chacha",
          "version": "0.3.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_chacha-0.3.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rand_core@0.6.4",
          "name": "rand_core",
          "version": "0.6.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand_core-0.6.4"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
          "name": "rustfft",
          "version": "6.2.0",
          "manifest_path": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scoped-tls@1.0.1",
          "name": "scoped-tls",
          "version": "1.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scoped-tls-1.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#strength_reduce@0.2.4",
          "name": "strength_reduce",
          "version": "0.2.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strength_reduce-0.2.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.48",
          "name": "syn",
          "version": "2.0.48",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.48"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#transpose@0.2.2",
          "name": "transpose",
          "version": "0.2.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/transpose-0.2.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#version_check@0.9.4",
          "name": "version_check",
          "version": "0.9.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/version_check-0.9.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasi@0.11.0+wasi-snapshot-preview1",
          "name": "wasi",
          "version": "0.11.0+wasi-snapshot-preview1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasi-0.11.0+wasi-snapshot-preview1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.90",
          "name": "wasm-bindgen",
          "version": "0.2.90",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.90"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.90",
          "name": "wasm-bindgen-backend",
          "version": "0.2.90",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.90"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-futures@0.4.40",
          "name": "wasm-bindgen-futures",
          "version": "0.4.40",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-futures-0.4.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.90",
          "name": "wasm-bindgen-macro",
          "version": "0.2.90",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.90"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.90",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.90",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.90"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.90",
          "name": "wasm-bindgen-shared",
          "version": "0.2.90",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.90"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test@0.3.40",
          "name": "wasm-bindgen-test",
          "version": "0.3.40",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-0.3.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-test-macro@0.3.40",
          "name": "wasm-bindgen-test-macro",
          "version": "0.3.40",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-test-macro-0.3.40"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.67",
          "name": "web-sys",
          "version": "0.3.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.67"
        }
      ],
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 554203,
      "ppid": 554143,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:6a0f63771649a8be:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
      "pid": 554203,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:e4a69f4d71ba66e6:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "6437a850e1b787aac4e798558f133afbe0564bc6506044196dc91cfdb4dfbc0a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:14a6c9e2c3add19e:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "a2edf192d21e9907013f8968ae53232ee4a2c249f101143a9a5999dc237800f8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:5f271300f5ecfaf2:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "d833e5af2fe21a1b32965499d18a6ec2a25545bb991ce9674a364851d06160df",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:b0bc125b0b6186fa:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "dc79c8abc1eed44ee061019c51f5fa79ca1a7b8112b4fc1356aca45e548d1cf5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:138bd5ad47ddd299:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "75744d21224121c5ca6d73536367ddac3c7c339488016e42440f8a74fd236082",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:2b7a1d8d359eaa93:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "ad08084d61dc32be1c7f85691e9e973256ceee9cc53dd47ff150b90493a380ea",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:56e9cbb7f0898d7f:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "dad27a1e9400abe51ff173f4683627ed38b079def6099169e68761540e6fdb7c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:a68ebd0239309417:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "8dcc64f78a4b29b0a288f34965f2cde81b7af8465ab483d77eb29dee6acf2f2d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "used:cc:fd90d2709987b7e4:60cec5695b751425:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
      "pid": 554203,
      "sha256": "197f2b51d1e298fd95726267e40617336337134065147c3068f766b3fd604153",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
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
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 554203,
      "ppid": 554143,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
        "/target/debug/build/rustfft-df5ef03d367a47e7",
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
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustc7Osm21/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0ajsgqe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libversion_check-ee556ce3fb13c2b4.rlib(version_check-ee556ce3fb13c2b4.version_check.8432150681c8a178-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-554203-1783994761424653306.map",
      "pid": 554203,
      "ppid": 554143,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-554203-1783994761424653306.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "exit_code": 0,
      "kind": "exec",
      "pid": 554230,
      "ppid": 554169,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-integer",
      "cargo_pkg_version": "0.1.45",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "event_id": "used:cc:951da16589636ef0:c5ebf34275ab6627:0525545e6d709c1c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
      "pid": 554230,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-integer",
      "cargo_pkg_version": "0.1.45",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "event_id": "used:cc:951da16589636ef0:5909e849dfede5f1:0525545e6d709c1c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
      "pid": 554230,
      "sha256": "abde26479486c8b97136f79e09a61466c5e6af08583141313d53f77b1f36b972",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-integer",
      "cargo_pkg_version": "0.1.45",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "event_id": "used:cc:951da16589636ef0:0ba06bcda6caddf5:0525545e6d709c1c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
      "pid": 554230,
      "sha256": "0d24f03a096241fd10e919cb74830596c5ba68ee9bc21355d0e60ddf55b3dd53",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
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
      "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "cargo_pkg_name": "num-integer",
      "cargo_pkg_version": "0.1.45",
      "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 554230,
      "ppid": 554169,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
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
          "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA",
          "kind": "object",
          "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcIoSzOA/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
          "kind": "object",
          "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
          "kind": "object",
          "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-554230-1783994761443450627.map",
      "pid": 554230,
      "ppid": 554169,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-554230-1783994761443450627.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "exit_code": 0,
      "kind": "exec",
      "pid": 554229,
      "ppid": 554168,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.15",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "event_id": "used:cc:10dd48d5a331e0dc:cd06019a3355a5a0:817d5ec450636eb3",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
      "path": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
      "pid": 554229,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.15",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "event_id": "used:cc:10dd48d5a331e0dc:1a3540513fe3f338:817d5ec450636eb3",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
      "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
      "pid": 554229,
      "sha256": "19590024724d0923fe431bd0e9dcb4d3e97e1becb0837bbd4d35dae66f73ef07",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.15",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "event_id": "used:cc:10dd48d5a331e0dc:25cb5d4c3f3c317c:817d5ec450636eb3",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
      "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
      "pid": 554229,
      "sha256": "c4e0b005f110a15b1e99b5cce1d8396ca9cd35ca39de74fc2c1aa04f44d7f1de",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
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
      "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.15",
      "context_path": "/tmp/native-trace-551044-1783994758300/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-551044-1783994758300/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 554229,
      "ppid": 554168,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-55afc35e88511a79.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd",
        "/target/debug/build/num-traits-381059396003c1df",
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
          "directory": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd",
          "kind": "object",
          "path": "/target/debug/build/num-traits-381059396003c1df/rustcAHQRdd/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-381059396003c1df",
          "kind": "object",
          "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-381059396003c1df",
          "kind": "object",
          "path": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-55afc35e88511a79.rlib(autocfg-55afc35e88511a79.autocfg.f6db541c64b6ce2a-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-554229-1783994761442042424.map",
      "pid": 554229,
      "ppid": 554168,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-554229-1783994761442042424.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
      "parsed_event_count": 1343,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1345,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "d5eaa1 ...\n18.147  rustc            559793 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_10\", \"v2_12\", \"v2_14\", \"v2_16\", \"v2_18\", \"v2_20\", \"v2_22\", \"v2_24\", \"v2_26\", \"v2_28\", \"v2_30\", \"v2_32\",  -C metadata=e32b5cbb99549cb2 ...\n18.153  rustc            559783 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=5bf917358a455423 ...\n18.156  rustc            559784 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=2bccf65b8fe5aec7 ...\n18.168  rustc            559795 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=e06e72fa969977d5 ...\n18.170  cargo            559798 558269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n18.172  rustc            559786 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=7162d9a34f79e387 ...\n18.192  rustc            559796 555865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) -C metadata=a916acebc876ca5c ...\n18.207  rustup           559817 543883   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.207  rustc            559815 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.255  rustc            559850 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n18.278  rustc            559849 559798   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"mint\", \"rand\", \"serde\", \"swizzle\", \"unstable\")) -C metadata=d5e815ac590d38c1 ...\n18.324  cc               559887 559783   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/atk-sys-f47ee198205ea3f3/rustcJsBuIv/symbols.o /target/debug/build/atk-sys-f47ee198205ea3f3/build_script_build-f47ee198205ea3f3.build_script_build.6b553cd55fd300f5-cgu.0.rcgu. /target/debug/build/atk-sys-f47ee198205ea3f3/build_script_build-f47ee198205ea3f3.5yhyvlw2cek213c8436sxkt0e.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.331  cc               559909 559887   0 \n18.348  collect2         559914 559909   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI88GpP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.348  ld.lld           559915 559914   0 \n18.348  rust-lld         559915 559914   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccI88GpP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.357  cc               559920 559741   0 /tmp/native-trace-558407-1783994775060/shims/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcTPr6aj/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.0ry9q5y.rcgu.o ...\n18.361  cc               559922 559920   0 /usr/bin/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcTPr6aj/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.0ry9q5y.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.0ry9q5y.rcgu.o ...\n18.365  collect2         559924 559922   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.368  ld.lld           559925 559924   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3 ...\n18.370  rust-lld         559925 559924   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxoYwNS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.374  cc               559921 559789   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gio-sys-41f6433ceda9a0d5/rustc4egNef/symbols.o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.build_script_build.9c3da3e30cad326f-cgu.0.rcgu. /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.albec7xtawunadop6wo7az1t6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.408  cc               559962 559788   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/rustcGMFXS1/symbols.o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.build_script_build.1bf53d0482f122 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.7utbj96wgsp3ll0xkch2aun1h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.408  cc               559968 559962   0 /usr/bin/cc -m64 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/rustcGMFXS1/symbols.o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.build_script_build.1bf53d0482f122 /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef.7utbj96wgsp3ll0xkch2aun1h.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.413  collect2         559970 559968   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.418  ld.lld           559971 559970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/javascriptcore-rs-sys-8731d3a59eb5fbef/build_script_build-8731d3a59eb5fbef ...\n18.420  cc               559969 559782   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/cairo-sys-rs-ae88d44245f39edc/rustch3GmSw/symbols.o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.build_script_build.dc2856f2b8dd5f42-cgu.0. /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.98vnos2lhvdlr7gy3ubslziu7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.423  rust-lld         559971 559970   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpb51lu.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.436  cargo            559974 558399   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n18.439  cc               559975 559969   0 /usr/bin/cc -m64 /target/debug/build/cairo-sys-rs-ae88d44245f39edc/rustch3GmSw/symbols.o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.build_script_build.dc2856f2b8dd5f42-cgu.0. /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc.98vnos2lhvdlr7gy3ubslziu7.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.445  collect2         559978 559975   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.447  ld.lld           559981 559978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cairo-sys-rs-ae88d44245f39edc/build_script_build-ae88d44245f39edc ...\n18.452  cc               559977 559921   0 /usr/bin/cc -m64 /target/debug/build/gio-sys-41f6433ceda9a0d5/rustc4egNef/symbols.o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.build_script_build.9c3da3e30cad326f-cgu.0.rcgu. /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5.albec7xtawunadop6wo7az1t6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.452  rust-lld         559981 559978   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccA8M2kG.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.466  collect2         559989 559977   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.475  ld.lld           560000 559989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gio-sys-41f6433ceda9a0d5/build_script_build-41f6433ceda9a0d5 ...\n18.477  rust-lld         560000 559989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJh5ip1.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.482  rustc            560001 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.496  rustc            560011 558513   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rand --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rand-0.3.23/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128_support\", \"nightly\")) -C metadata=e7b790f7c7e88113 ...\n18.503  build-script-bu  560031 559715   0 /target/debug/build/cgmath-d9745ec9a83e1cb3/build-script-build\n18.514  cc               560025 559787   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/pango-sys-7efecf5bb9a79701/rustcs5ziyZ/symbols.o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.build_script_build.eff4b66755a69e8f-cgu.0.rcg /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.e93n4i0ez3790mcryu9uaevuk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.527  cc               560077 559765   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/glib-sys-49a54380333624c7/rustcb9cN9D/symbols.o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.build_script_build.92c46b64b0c2d7aa-cgu.0.rcgu /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.9ha3novm5hzziw455s8wcgcry.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.529  cc               560093 560077   0 /usr/bin/cc -m64 /target/debug/build/glib-sys-49a54380333624c7/rustcb9cN9D/symbols.o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.build_script_build.92c46b64b0c2d7aa-cgu.0.rcgu /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7.9ha3novm5hzziw455s8wcgcry.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.532  cc               560091 559781   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gdk-sys-ac0b5d633e2bdb61/rustcYzaMfy/symbols.o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.build_script_build.7da4f7b49862835b-cgu.0.rcgu. /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.dz0s08lzzuodtl1o3jr6a513i.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.532  cc               560095 560091   0 /usr/bin/cc -m64 /target/debug/build/gdk-sys-ac0b5d633e2bdb61/rustcYzaMfy/symbols.o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.build_script_build.7da4f7b49862835b-cgu.0.rcgu. /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61.dz0s08lzzuodtl1o3jr6a513i.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.538  collect2         560104 560093   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.540  ld.lld           560105 560104   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/glib-sys-49a54380333624c7/build_script_build-49a54380333624c7 ...\n18.541  rust-lld         560105 560104   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc34QSyX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.543  collect2         560106 560095   0 \n18.549  ld.lld           560107 560106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxQz3pX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-sys-ac0b5d633e2bdb61/build_script_build-ac0b5d633e2bdb61 ...\n18.557  rust-lld         560107 560106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccxQz3pX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.558  cc               560108 559849   0 /tmp/native-trace-558269-1783994774811/shims/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcumA3so/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.1465ffj.rcgu.o ...\n18.563  cc               560109 560108   0 /usr/bin/cc -m64 /target/debug/build/cgmath-d9745ec9a83e1cb3/rustcumA3so/symbols.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.03uss0xtkaau14p08o0tlmof6.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.0r6l6tsg0irdohnbnsckwmiy1.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.1q7tyhaeyuxjcgseugegqrdb7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2ckumcps84uxgmn3eidq0d3s8.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.2g43c8a10av91t1cmu7husmkk.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.36olalb1cotkalmrs74kuhnvt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3muur7clyp0tx2veektlgu1l3.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3okod7qlsc5lwtxidxozsg8jx.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3xibijepu2notol3ukfrpfu9j.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.3zlyugjkhuuyws5jp6ky8vxp4.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.4gf0qv8cv1db44suivyof20c7.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.59rhfqxba2fkbl8drbwapk56n.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5dh58l14cuwycfbw9tp9mexma.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5i83esvpup7ltazqvffgo7u0w.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5wnqq3w9kknyc9umpqm8909zw.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.5xccqzyhi3ac6w1sw7c5ylrrt.1465ffj.rcgu.o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3.69f42sa8wr5l0bpx73c7o13je.1465ffj.rcgu.o ...\n18.565  cc               560114 560025   0 /usr/bin/cc -m64 /target/debug/build/pango-sys-7efecf5bb9a79701/rustcs5ziyZ/symbols.o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.build_script_build.eff4b66755a69e8f-cgu.0.rcg /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701.e93n4i0ez3790mcryu9uaevuk.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.575  rustc            560121 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_30\", \"v2_32\", \"v2_34\", \"v2_38\", \"v2_46\", \"v2_50\")) -C metadata=5bf917358a455423 ...\n18.575  rustc            560124 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gobject-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_62\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=2bccf65b8fe5aec7 ...\n18.576  collect2         560123 560109   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.579  ld.lld           560134 560123   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/cgmath-d9745ec9a83e1cb3/build_script_build-d9745ec9a83e1cb3 ...\n18.580  rustc            560119 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gio-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=b6c73f6fbaf20e62 ...\n18.581  rust-lld         560134 560123   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccigCgT3.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.581  rustc            560132 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glib-sys-0.18.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_58\", \"v2_60\", \"v2_62\", \"v2_64\", \"v2_66\", \"v2_68\", \"v2_70\", \"v2_72\", \"v2_74\", \"v2_76\", \"v2_78\")) -C metadata=bba6f3e8691efe52 ...\n18.582  rustc            560133 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gtk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\", \"v3_24_1\", \"v3_24_11\", \"v3_24_30\", \"v3_24_8\", \"v3_24_9\")) -C metadata=7162d9a34f79e387 ...\n18.592  rustc            560136 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cairo-sys-rs-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"freetype\", \"glib\", \"pdf\", \"png\", \"ps\", \"script\", \"svg\", \"use_glib\", \"v1_16\", \"v1_18\", \"win32-surface\", \"win -C metadata=d4233a0aa2d5eaa1 ...\n18.593  collect2         560122 560114   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.598  rustc            560102 558513   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crypto --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"with-bench\")) -C metadata=46585077d76dd543 ...\n18.601  rustc            560127 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-pixbuf-sys-0.18.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_40\", \"v2_42\")) -C metadata=e06e72fa969977d5 ...\n18.609  ld.lld           560164 560122   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/pango-sys-7efecf5bb9a79701/build_script_build-7efecf5bb9a79701 ...\n18.613  rustc            560144 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n18.613  rustc            560183 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name vcpkg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/vcpkg-0.2.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=69468eef4ea66cf5 ...\n18.616  cc               560158 559793   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/rustcGKvPdM/symbols.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2k8kbs1rkryvtfacr12ooncqg.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.90ckgnps9ruu1fqleiqxl5bxe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.akwn53nutluvdp20f1xzpmqas.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.aunsk96f9wyur5k7oolfa03je.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dhjob3n77402m3wau53fiahdv.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dn9kexccof6r8ptg9nfy34hfe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2qy2xs7ln0v0m11xspllg458l.14n1pjl.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib ...\n18.619  rust-lld         560164 560122   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cckYQiGb.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.629  cc               560184 560158   0 /usr/bin/cc -m64 /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/rustcGKvPdM/symbols.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2k8kbs1rkryvtfacr12ooncqg.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.90ckgnps9ruu1fqleiqxl5bxe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.akwn53nutluvdp20f1xzpmqas.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.aunsk96f9wyur5k7oolfa03je.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dhjob3n77402m3wau53fiahdv.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.dn9kexccof6r8ptg9nfy34hfe.14n1pjl.rcgu.o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722.2qy2xs7ln0v0m11xspllg458l.14n1pjl.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib ...\n18.649  cc               560189 559786   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/rustcOUir17/symbols.o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.build_script_build.f02832431664dc17-cgu.0.rcgu. /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.4dzkytt7zrst7bnu5zedry4t4.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.652  cc               560096 559795   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/rustcPsuPWx/symbols.o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.build_script_build.25504bd235bc3179-cgu. /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.28t6hu43ubqewqkd5y2hurn55.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.657  cc               560224 560096   0 /usr/bin/cc -m64 /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/rustcPsuPWx/symbols.o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.build_script_build.25504bd235bc3179-cgu. /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499.28t6hu43ubqewqkd5y2hurn55.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.661  rustc            560220 559974   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pkg_config --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4287493f147b149e ...\n18.662  collect2         560225 560224   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.666  ld.lld           560226 560225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gdk-pixbuf-sys-1c6aaef29d7c0499/build_script_build-1c6aaef29d7c0499 ...\n18.670  cc               560219 560189   0 /usr/bin/cc -m64 /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/rustcOUir17/symbols.o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.build_script_build.f02832431664dc17-cgu.0.rcgu. /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54.4dzkytt7zrst7bnu5zedry4t4.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.672  rust-lld         560226 560225   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccm8xj55.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n18.689  rustc            560231 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_10\", \"v2_12\", \"v2_14\", \"v2_16\", \"v2_18\", \"v2_20\", \"v2_22\", \"v2_24\", \"v2_26\", \"v2_28\", \"v2_30\", \"v2_32\",  -C metadata=e32b5cbb99549cb2 ...\n18.710  rustc            560135 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/soup3-sys-0.5.0/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_0\", \"v3_2\", \"v3_4\")) -C metadata=a916acebc876ca5c ...\n18.719  cc               560223 559796   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/soup3-sys-41647c642ee4ea07/rustcuGAAHH/symbols.o /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.build_script_build.4682c6ad9c7646bb-cgu.0.rcg /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.dndse5oijzuyee2zqpbg1965m.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.722  rustc            560253 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/javascriptcore-rs-sys-1.1.1/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v2_28\", \"v2_38\")) -C metadata=0de86063c84085c3 ...\n18.727  cc               560264 560223   0 /usr/bin/cc -m64 /target/debug/build/soup3-sys-41647c642ee4ea07/rustcuGAAHH/symbols.o /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.build_script_build.4682c6ad9c7646bb-cgu.0.rcg /target/debug/build/soup3-sys-41647c642ee4ea07/build_script_build-41647c642ee4ea07.dndse5oijzuyee2zqpbg1965m.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.731  collect2         560257 560219   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSApDil.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.746  collect2         560199 560184   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n18.750  rustc            560265 555854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/gdk-sys-0.18.2/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"v3_24\")) -C metadata=36447ea903029f40 ...\n18.759  ld.lld           560276 560199   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/webkit2gtk-sys-2327932fb8f2b722/build_script_build-2327932fb8f2b722 ...\n18.761  build-script-bu  560281 559798   0 /target/debug/build/cgmath-d9745ec9a83e1cb3/build-script-build\n18.764  cc               560269 559784   0 /tmp/native-trace-555477-1783994768049/shims/cc -m64 /target/debug/build/gobject-sys-32eddc0241afc4ef/rustc2llJ4Z/symbols.o /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.build_script_build.1670ac7eb87fbcd9-cgu.0.r /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.9iycmgyd8j08udj0zzgiapsqw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.769  ld.lld           560268 560257   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccSApDil.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/gtk-sys-86c8a3bcf5fa9b54/build_script_build-86c8a3bcf5fa9b54 ...\n18.773  cc               560291 560269   0 /usr/bin/cc -m64 /target/debug/build/gobject-sys-32eddc0241afc4ef/rustc2llJ4Z/symbols.o /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.build_script_build.1670ac7eb87fbcd9-cgu.0.r /target/debug/build/gobject-sys-32eddc0241afc4ef/build_script_build-32eddc0241afc4ef.9iycmgyd8j08udj0zzgiapsqw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsystem_deps-c553d643752db728.rlib /target/debug/deps/libversion_compare-336196971b9e686a.rlib /target/debug/deps/libpkg_config-15486b590baf4edc.rlib /target/debug/deps/libcfg_expr-d01aaca818bc3c83.rlib /target/debug/deps/libtarget_lexicon-ba98665cc258ed83.rlib /target/debug/deps/libsmallvec-9301d3919297f9f5.rlib /target/debug/deps/libtoml-3cc28690982a3a8a.rlib /target/debug/deps/libtoml_edit-cce410826a09d098.rlib /target/debug/deps/libserde_spanned-3c91bdab800ae8f6.rlib /target/debug/deps/libindexmap-4f1a333b58ee667e.rlib /target/debug/deps/libequivalent-09a05a12e658fb17.rlib /target/debug/deps/libhashbrown-376ddd616f0223c3.rlib /target/debug/deps/libwinnow-4c821fba5e6511f7.rlib ...\n18.780  rust-lld         560276 560199   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoBPfOZ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n"
    },
    {
      "argv": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554344,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
      "pid": 554344,
      "ppid": 553907,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554344,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554347,
      "ppid": 554344,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
      "pid": 554351,
      "ppid": 553907,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554353,
      "ppid": 554351,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/num-traits-381059396003c1df/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
      "pid": 554358,
      "ppid": 553907,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554359,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554370,
      "ppid": 554351,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554371,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554392,
      "ppid": 554351,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/bin/rustc",
        "--crate-name",
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/bin/rustc",
      "pid": 554393,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe2",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554424,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe3",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554431,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe4",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554438,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe5",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554445,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe6",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554452,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "rustfft",
      "cwd": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "event_id": "bsrun:49e6d5f006c43d05:ffaac7c3e4ef67e2:e1f030fe76560b4d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
      "out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
      "success": true,
      "target": null,
      "version": "6.2.0",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-riscv64-hjkr5f5l/src/rustfft-6.2.0",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "num-integer",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "event_id": "bsrun:5941c1f02bcc48da:e3ea911469aa909d:124bf4a09cbfe4a7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "out_dir": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
      "success": true,
      "target": null,
      "version": "0.1.45",
      "_owner": {
        "crate": "num-integer",
        "version": "0.1.45",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "num-traits",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "event_id": "bsrun:f771365925bccf2d:90a61dfcdcd2850a:d216b3ab71bccee5",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "out_dir": "/target/debug/build/num-traits-381059396003c1df/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
      "success": true,
      "target": null,
      "version": "0.2.15",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
      "build_script_root_pid": 554344,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554347,
      "ppid": 554344,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554353,
      "ppid": 554351,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554359,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554370,
      "ppid": 554351,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554371,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-integer-6ddb53f891fc2468/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554351,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554392,
      "ppid": 554351,
      "root_cargo_pid": 553907,
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
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/bin/rustc",
      "pid": 554393,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554424,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554431,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554438,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "probe5",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554445,
      "ppid": 554358,
      "root_cargo_pid": 553907,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/num-traits-256baccfe6eb4d1b/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 554358,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 554452,
      "ppid": 554358,
      "root_cargo_pid": 553907,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 2232,
    "crate": "rustfft",
    "version": "6.2.0",
    "crate_id": "880",
    "version_id": "1022294",
    "downloads": 5972519,
    "cumulative_downloads": 103252877567,
    "cumulative_share_of_global": 0.38603867269579356,
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
