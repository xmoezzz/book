# `rustfft` `6.2.0`

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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
    "/target/debug/build/rustfft-df5ef03d367a47e7",
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
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-556879-1783994771836987197.map",
  "pid": 556879,
  "ppid": 556786,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-556879-1783994771836987197.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0"
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
      "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
      "name": "rustfft",
      "version": "6.2.0",
      "manifest_path": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0"
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
  "pid": 556637,
  "ppid": 556517,
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

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
  "event_id": "used:cc:951da16589636ef0:5e628c6a67b5b31a:0525545e6d709c1c",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
  "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
  "pid": 556637,
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

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
  "pid": 556637,
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

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
  "pid": 556637,
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

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
  "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 556637,
  "ppid": 556517,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_owner": {
    "crate": "num-integer",
    "version": "0.1.45",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-integer@0.1.45",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk",
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
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
      "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk",
      "kind": "object",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-556637-1783994771562061943.map",
  "pid": 556637,
  "ppid": 556517,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-556637-1783994771562061943.map"
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

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
  "pid": 556618,
  "ppid": 556514,
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

#### Record 10

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
  "event_id": "used:cc:10dd48d5a331e0dc:410a9663599996b8:817d5ec450636eb3",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
  "path": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
  "pid": 556618,
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

#### Record 11

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
  "pid": 556618,
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

#### Record 12

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
  "pid": 556618,
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

#### Record 13

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
    "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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

#### Record 14

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
  "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 556618,
  "ppid": 556514,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.15",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.15",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN",
    "/target/debug/build/num-traits-381059396003c1df",
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
      "directory": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN",
      "kind": "object",
      "path": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-556618-1783994771550927698.map",
  "pid": 556618,
  "ppid": 556514,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-556618-1783994771550927698.map"
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

#### Record 16

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 556879,
  "ppid": 556786,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:d5bdbff580f3ec2d:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
  "pid": 556879,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:d41122c6b703436e:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "5e3a58140e55fdc78e2ecc094f666f1f4a376c7cde8b76557cf85cb2f6473bbf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:84a0ffdce8366495:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "46aa930f953b5c3f4fa1ed88441d8391763e733bb68efd7638c24b9287907254",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:854685fd4fba8c4d:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "c37d07b10f9c15732555518c429eb3a5be5e5c1dbeeacc4071165731e8dac99d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:4bab106b4e3573fa:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "e067560a47a2aa50be5a87f5f296643f8fdc22552ca95cb60472a5e1969762dd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:dc4e43c0e8097113:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "2f654a8ad2c98efcefb4b9b10f8a7a795c4924c84004ef06bb0461acd515b7b7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:a1e68d0afed22211:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "dfedc8068cdc89f034b7988a0200317332c9fc9ef322c69b9972eb1f500fb219",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:eaaadfb4582987d8:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "28e866d181d0de30ed4116926c545b5bde1a306adc8b0c6f45010597a8643a2d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:8677398710c6ba0b:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "2eed0991c8065ea577187aaaf6811a0667390482934ca2ae5c9d1499529dba30",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "used:cc:13de6f15aa0d131c:a081759979fc4c6b:e1e632a3f7f81507",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
  "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
  "pid": 556879,
  "sha256": "197f2b51d1e298fd95726267e40617336337134065147c3068f766b3fd604153",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "cargo_pkg_name": "rustfft",
  "cargo_pkg_version": "6.2.0",
  "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 556879,
  "ppid": 556786,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
    "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
    "/target/debug/build/rustfft-df5ef03d367a47e7",
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
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
      "kind": "object",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-556879-1783994771836987197.map",
  "pid": 556879,
  "ppid": 556786,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-556879-1783994771836987197.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
  "parse_error_count": 1,
  "parsed_event_count": 2037,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 2038,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "L::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.276  sh               563925 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.280  perl             563926 563925   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kdfs/x942kdf.c.in\n20.280  perl             563927 563924   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kdfs/tls1_prf.c.in\n20.293  sh               563928 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.299  perl             563929 563928   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ec_kem.c.in\n20.310  sh               563930 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.314  perl             563931 563930   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ecx_kem.c.in\n20.316  sh               563932 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.318  perl             563933 563932   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ml_kem_kem.c.in\n20.322  sh               563934 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.324  sh               563936 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.324  perl             563935 563934   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/rsa_kem.c.in\n20.330  perl             563937 563936   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ecx_kmgmt.c.in\n20.331  sh               563938 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.334  sh               563939 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.334  perl             563940 563938   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/lms_kmgmt.c.in\n20.339  perl             563941 563939   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ml_dsa_kmgmt.c.in\n20.342  sh               563942 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.346  sh               563944 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.348  perl             563943 563942   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ml_kem_kmgmt.c.in\n20.351  perl             563945 563944   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/mlx_kmgmt.c.in\n20.361  sh               563946 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.363  perl             563947 563946   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/slh_dsa_kmgmt.c.in\n20.369  sh               563948 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.374  perl             563949 563948   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/template_kmgmt.c.in\n20.421  sh               563950 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.424  sh               563952 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.424  perl             563951 563950   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/cmac_prov.c.in\n20.428  perl             563953 563952   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/gmac_prov.c.in\n20.432  sh               563954 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.436  perl             563955 563954   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/hmac_prov.c.in\n20.451  sh               563956 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.454  sh               563958 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.455  perl             563957 563956   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/kmac_prov.c.in\n20.459  sh               563959 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.461  perl             563960 563958   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/poly1305_prov.c.in\n20.465  perl             563961 563959   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/siphash_prov.c.in\n20.465  sh               563962 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.470  perl             563963 563962   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_ctr.c.in\n20.471  sh               563964 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.473  perl             563965 563964   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_hash.c.in\n20.475  sh               563966 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.476  perl             563967 563966   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_hmac.c.in\n20.479  sh               563968 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.482  perl             563969 563968   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/fips_crng_test.c.in\n20.484  sh               563970 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.487  perl             563971 563970   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/seed_src.c.in\n20.492  sh               563972 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.496  perl             563973 563972   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/seed_src_jitter.c.in\n20.508  sh               563974 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.512  perl             563975 563974   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/test_rng.c.in\n20.516  sh               563976 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.521  perl             563977 563976   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/dsa_sig.c.in\n20.537  sh               563978 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.541  perl             563979 563978   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/ecdsa_sig.c.in\n20.572  sh               563980 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.575  perl             563981 563980   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/eddsa_sig.c.in\n20.581  sh               563982 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.583  perl             563983 563982   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/ml_dsa_sig.c.in\n20.591  sh               563984 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.593  sh               563985 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.595  perl             563986 563985   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/slh_dsa_sig.c.in\n20.599  sh               563987 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.602  perl             563988 563984   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/rsa_sig.c.in\n20.605  perl             563989 563987   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/sm2_sig.c.in\n20.620  sh               563990 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.623  perl             563991 563990   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/skeymgmt/generic.c.in\n20.625  sh               563992 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.630  perl             563993 563992   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/file_store.c.in\n20.631  sh               563994 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.633  sh               563995 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.636  perl             563997 563995   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/winstore_store.c.in\n20.636  perl             563996 563994   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/file_store_any2obj.c.in\n20.641  sh               563998 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfig.cmake.in > OpenSSLC\n20.644  sh               563999 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfig.cmake.in > export\n20.647  perl             564001 563999   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfig.cmake.in\n20.647  perl             564000 563998   0 /usr/bin/perl -I. -Mconfigdata -Mbuilddata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfig.cmake.in\n20.671  sh               564002 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/libcrypto.pc.in > exporter\n20.675  perl             564003 564002   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/libcrypto.pc.in\n20.675  sh               564004 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/libssl.pc.in > exporters/l\n20.681  perl             564005 564004   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/libssl.pc.in\n20.682  sh               564006 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mbuilddata\" \"-Mbuilddata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/\n20.685  perl             564007 564006   0 /usr/bin/perl -I. -Mconfigdata -Mbuilddata -Mbuilddata -Mbuilddata util/dofile.pl -oMakefile exporters/pkg-config/openssl.pc.in\n20.772  sh               564008 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfigVersi\n20.774  perl             564009 564008   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Mbuilddata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfigVersion.cmake.in\n20.777  sh               564010 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfigVer\n20.778  perl             564011 564010   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfigVersion.cmake.in\n20.800  sh               564012 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-con\n20.801  perl             564013 564012   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/openssl.pc.in\n20.865  sh               564014 563792   0 /bin/sh -c \"/usr/bin/make\" depend && \"/usr/bin/make\" _build_libs\n20.866  make             564015 564014   0 /usr/bin/make depend\n20.883  sh               564016 564015   0 /bin/sh -c : \n20.885  sh               564017 564015   0 /bin/sh -c /usr/bin/perl ./util/add-depends.pl \"gcc\"\n20.887  perl             564018 564017   0 /usr/bin/perl ./util/add-depends.pl gcc\n20.951  sh               564019 564015   0 /bin/sh -c : \n20.953  make             564020 564014   0 /usr/bin/make _build_libs\n20.969  sh               564021 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.969  sh               564022 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.972  sh               564023 564020   0 \n20.972  aarch64-linux-g  564027 564023   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.972  aarch64-linux-g  564024 564021   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.972  aarch64-linux-g  564025 564022   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.973  sh               564026 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.975  cc1              564028 564024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_libctx.d -MF apps/lib/libapps-lib-app_libctx.d.tmp -MQ apps/lib/libapps-lib-app_libctx.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.975  aarch64-linux-g  564030 564026   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.975  sh               564029 564020   0 \n20.977  sh               564032 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.977  aarch64-linux-g  564031 564029   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.977  sh               564034 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.977  cc1              564033 564030   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_rand.d -MF apps/lib/libapps-lib-app_rand.d.tmp -MQ apps/lib/libapps-lib-app_rand.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.980  sh               564036 564020   0 \n20.980  cc1              564035 564025   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_params.d -MF apps/lib/libapps-lib-app_params.d.tmp -MQ apps/lib/libapps-lib-app_params.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.980  aarch64-linux-g  564039 564034   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.983  aarch64-linux-g  564037 564032   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.984  sh               564038 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.986  aarch64-linux-g  564040 564036   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.986  cc1              564042 564031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_x509.d -MF apps/lib/libapps-lib-app_x509.d.tmp -MQ apps/lib/libapps-lib-app_x509.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.987  cc1              564041 564027   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_provider.d -MF apps/lib/libapps-lib-app_provider.d.tmp -MQ apps/lib/libapps-lib-app_provider.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.987  sh               564044 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.989  cc1              564043 564039   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps_opt_printf.d -MF apps/lib/libapps-lib-apps_opt_printf.d.tmp -MQ apps/lib/libapps-lib-apps_opt_printf.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.991  cc1              564047 564037   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps.d -MF apps/lib/libapps-lib-apps.d.tmp -MQ apps/lib/libapps-lib-apps.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.995  cc1              564048 564040   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps_ui.d -MF apps/lib/libapps-lib-apps_ui.d.tmp -MQ apps/lib/libapps-lib-apps_ui.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.997  aarch64-linux-g  564045 564044   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.997  aarch64-linux-g  564049 564038   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.000  sh               564046 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.000  cc1              564050 564049   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-columns.d -MF apps/lib/libapps-lib-columns.d.tmp -MQ apps/lib/libapps-lib-columns.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.004  aarch64-linux-g  564051 564046   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.004  sh               564052 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.006  cc1              564053 564045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-engine.d -MF apps/lib/libapps-lib-engine.d.tmp -MQ apps/lib/libapps-lib-engine.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.007  sh               564055 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.008  aarch64-linux-g  564054 564052   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.009  cc1              564056 564051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-engine_loader.d -MF apps/lib/libapps-lib-engine_loader.d.tmp -MQ apps/lib/libapps-lib-engine_loader.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.010  aarch64-linux-g  564058 564055   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.012  sh               564057 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.015  aarch64-linux-g  564061 564057   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.015  sh               564060 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.017  cc1              564059 564054   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-fmt.d -MF apps/lib/libapps-lib-fmt.d.tmp -MQ apps/lib/libapps-lib-fmt.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.019  aarch64-linux-g  564063 564060   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.022  cc1              564065 564061   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-log.d -MF apps/lib/libapps-lib-log.d.tmp -MQ apps/lib/libapps-lib-log.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.022  cc1              564064 564058   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-http_server.d -MF apps/lib/libapps-lib-http_server.d.tmp -MQ apps/lib/libapps-lib-http_server.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.024  cc1              564066 564063   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-names.d -MF apps/lib/libapps-lib-names.d.tmp -MQ apps/lib/libapps-lib-names.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.027  sh               564062 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.032  aarch64-linux-g  564067 564062   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.040  cc1              564068 564067   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-opt.d -MF apps/lib/libapps-lib-opt.d.tmp -MQ apps/lib/libapps-lib-opt.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.050  as               564069 564054   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-fmt.o /tmp/ccaDaPuj.s\n21.079  touch            564070 564020   0 /usr/bin/touch apps/lib/libapps-lib-fmt.d.tmp\n21.085  sh               564071 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-lib-fm\n21.088  cmp              564072 564071   0 /usr/bin/cmp apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d\n21.094  mv               564073 564071   0 /usr/bin/mv apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d\n21.102  sh               564074 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.106  aarch64-linux-g  564075 564074   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.110  as               564076 564063   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-names.o /tmp/ccY8EL8X.s\n21.114  cc1              564077 564075   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-s_cb.d -MF apps/lib/libapps-lib-s_cb.d.tmp -MQ apps/lib/libapps-lib-s_cb.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.130  touch            564078 564020   0 /usr/bin/touch apps/lib/libapps-lib-names.d.tmp\n21.131  sh               564079 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-li\n21.133  cmp              564080 564079   0 /usr/bin/cmp apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d\n21.134  mv               564081 564079   0 /usr/bin/mv apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d\n21.137  sh               564082 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.139  aarch64-linux-g  564083 564082   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.142  cc1              564084 564083   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-s_socket.d -MF apps/lib/libapps-lib-s_socket.d.tmp -MQ apps/lib/libapps-lib-s_socket.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.160  as               564085 564039   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-apps_opt_printf.o /tmp/ccOTBCSc.s\n21.169  make             564086 563057   0 /tmp/native-trace-559618-1783994778377/shims/make depend\n21.171  make             564087 564086   0 /usr/bin/make depend\n21.181  touch            564088 564020   0 /usr/bin/touch apps/lib/libapps-lib-apps_opt_printf.d.tmp\n21.184  sh               564089 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n21.191  cmp              564090 564089   0 /usr/bin/cmp apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d\n21.195  mv               564091 564089   0 /usr/bin/mv apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d\n21.200  sh               564092 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.204  sh               564094 564087   0 /bin/sh -c : \n21.207  aarch64-linux-g  564093 564092   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.207  sh               564095 564087   0 /bin/sh -c /usr/bin/perl ./util/add-depends.pl \"gcc\"\n21.210  perl             564096 564095   0 /usr/bin/perl ./util/add-depends.pl gcc\n21.213  cc1              564097 564093   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-tlssrp_depr.d -MF apps/lib/libapps-lib-tlssrp_depr.d.tmp -MQ apps/lib/libapps-lib-tlssrp_depr.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.229  as               564098 564030   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_rand.o /tmp/cc7mOhTv.s\n21.239  as               564099 564061   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-log.o /tmp/cc5St0oR.s\n21.252  touch            564100 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_rand.d.tmp\n21.256  sh               564101 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/liba\n21.258  as               564102 564049   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-columns.o /tmp/ccJSc3YX.s\n21.262  cmp              564103 564101   0 /usr/bin/cmp apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d\n21.264  as               564105 564051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-engine_loader.o /tmp/ccXgwcY4.s\n21.267  touch            564104 564020   0 /usr/bin/touch apps/lib/libapps-lib-log.d.tmp\n21.267  mv               564106 564101   0 /usr/bin/mv apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d\n21.270  as               564107 564040   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-apps_ui.o /tmp/cclosUzh.s\n21.271  sh               564108 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-lib-lo\n21.274  as               564109 564024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_libctx.o /tmp/ccGeSkj2.s\n21.276  cmp              564110 564108   0 /usr/bin/cmp apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d\n21.281  mv               564111 564108   0 /usr/bin/mv apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d\n21.282  sh               564112 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha1-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/in\n21.283  as               564113 564045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-engine.o /tmp/ccMZ62SF.s\n21.287  perl             564114 564112   0 /usr/bin/perl crypto/aes/asm/aes-sha1-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.292  touch            564115 564020   0 /usr/bin/touch apps/lib/libapps-lib-columns.d.tmp\n21.295  sh               564116 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapp\n21.299  as               564118 564025   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_params.o /tmp/ccKVxgG7.s\n21.301  cmp              564117 564116   0 /usr/bin/cmp apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d\n21.301  as               564119 564027   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_provider.o /tmp/cc4Yc4xf.s\n21.303  mv               564120 564116   0 /usr/bin/mv apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d\n21.307  sh               564121 564114   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha1-armv8.S\"\n21.309  sh               564122 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha256-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/\n21.313  perl             564124 564122   0 /usr/bin/perl crypto/aes/asm/aes-sha256-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.313  perl             564125 564121   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha1-armv8.S\n21.316  touch            564123 564020   0 /usr/bin/touch apps/lib/libapps-lib-apps_ui.d.tmp\n21.320  touch            564126 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_libctx.d.tmp\n21.323  touch            564127 564020   0 /usr/bin/touch apps/lib/libapps-lib-engine.d.tmp\n21.326  touch            564128 564020   0 /usr/bin/touch apps/lib/libapps-lib-engine_loader.d.tmp\n21.328  sh               564129 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapp\n21.331  sh               564131 564087   0 /bin/sh -c : \n21.333  touch            564130 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_provider.d.tmp\n21.334  cmp              564132 564129   0 /usr/bin/cmp apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d\n21.335  mv               564134 564129   0 /usr/bin/mv apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d\n21.338  sh               564133 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/\n21.340  make             564137 564136   0 /usr/bin/make build_libs\n21.340  make             564136 563057   0 /tmp/native-trace-559618-1783994778377/shims/make build_libs\n21.340  sh               564135 564124   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha256-armv8.S\"\n21.342  perl             564138 564135   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha256-armv8.S\n21.345  sh               564139 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-\n21.347  sh               564141 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d > /dev/null 2> /dev/null; then \\\\n\trm -f app\n21.349  cmp              564140 564133   0 /usr/bin/cmp apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d\n21.349  cmp              564142 564139   0 /usr/bin/cmp apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d\n21.350  sh               564143 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/\n21.353  cmp              564145 564141   0 /usr/bin/cmp apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d\n21.353  as               564146 564031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_x509.o /tmp/ccEZcLyB.s\n21.354  cmp              564144 564143   0 /usr/bin/cmp apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d\n21.356  mv               564147 564141   0 /usr/bin/mv apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d\n21.360  mv               564148 564133   0 /usr/bin/mv apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d\n21.360  sh               564149 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha512-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/\n21.361  sh               564152 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.362  mv               564150 564143   0 /usr/bin/mv apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d\n21.365  mv               564151 564139   0 /usr/bin/mv apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d\n21.367  aarch64-linux-g  564154 564152   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.369  touch            564153 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_params.d.tmp\n21.371  cc1              564155 564154   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_cbc.d -MF crypto/aes/libcrypto-lib-aes_cbc.d.tmp -MQ crypto/aes/libcrypto-lib-aes_cbc.o -D_REENTRANT -D ...\n21.372  sh               564156 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.374  sh               564160 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/\n21.375  perl             564157 564149   0 /usr/bin/perl crypto/aes/asm/aes-sha512-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.375  sh               564161 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.376  sh               564158 564137   0 /bin/sh -c /usr/bin/perl util/mkinstallvars.pl COMMENT=\"This file should be used when building against this OpenSSL build, and should never\n21.376  sh               564162 564137   0 /bin/sh -c /usr/bin/perl util/mkinstallvars.pl \"PREFIX=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/o\n21.378  perl             564164 564162   0 /usr/bin/perl util/mkinstallvars.pl PREFIX=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install BINDIR=bin LIBDIR=lib libdir=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib INCLUDEDIR=include APPLINKDIR=include/openssl ENGINESDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/engines- MODULESDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/ossl-mod PKGCONFIGDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/pkgcon CMAKECONFIGDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/cmak LDLIBS=-ldl -pthread  VERSION=3.6.3\n21.380  sh               564167 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.380  sh               564166 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/crypto/bn_conf.h.in > include/crypto/bn_conf.h\n21.381  aarch64-linux-g  564159 564156   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.382  perl             564168 564166   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/crypto/bn_conf.h.in\n21.382  sh               564169 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/crypto/dso_conf.h.in > include/crypto/dso_conf.h\n21.383  perl             564165 564158   0 /usr/bin/perl util/mkinstallvars.pl COMMENT=This file should be used when building against this OpenSSL build, and should never be installed PREFIX=. BINDIR=apps APPLINKDIR=ms LIBDIR= INCLUDEDIR=include INCLUDEDIR=./include ENGINESDIR=engines MODULESDIR=providers VERSION=3.6.3 LDLIBS=-ldl -pthread \n21.383  sh               564170 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/asn1.h.in > include/openssl/asn1.h\n21.384  aarch64-linux-g  564172 564167   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.386  perl             564173 564170   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/asn1.h.in\n21.386  perl             564171 564169   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/crypto/dso_conf.h.in\n21.390  sh               564174 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/asn1t.h.in > include/openssl/asn1t.h\n21.391  sh               564177 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/bio.h.in > include/openssl/bio.h\n21.397  perl             564178 564174   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/asn1t.h.in\n21.397  cc1              564182 564172   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_ecb.d -MF crypto/aes/libcrypto-lib-aes_ecb.d.tmp -MQ crypto/aes/libcrypto-lib-aes_ecb.o -D_REENTRANT -D ...\n21.397  aarch64-linux-g  564163 564161   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.403  perl             564180 564177   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/bio.h.in\n21.405  sh               564181 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/cmp.h.in > include/openssl/cmp.h\n21.406  sh               564185 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/cms.h.in > include/openssl/cms.h\n21.406  cc1              564183 564163   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_core.d -MF crypto/aes/libcrypto-lib-aes_core.d.tmp -MQ crypto/aes/libcrypto-lib-aes_core.o -D_REENTRANT -D ...\n21.409  perl             564184 564181   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/cmp.h.in\n21.409  sh               564186 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/comp.h.in > include/openssl/comp.h\n21.411  perl             564188 564186   0 \n21.411  sh               564189 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/conf.h.in > include/openssl/conf.h\n21.412  sh               564175 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.413  perl             564187 564185   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/cms.h.in\n21.416  perl             564191 564189   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/conf.h.in\n21.417  cc1              564179 564159   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_cfb.d -MF crypto/aes/libcrypto-lib-aes_cfb.d.tmp -MQ crypto/aes/libcrypto-lib-aes_cfb.o -D_REENTRANT -D ...\n21.419  sh               564193 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/core_name\n21.420  cmp              564176 564160   0 /usr/bin/cmp apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d\n21.422  sh               564190 564157   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha512-armv8.S\"\n21.422  perl             564196 564193   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile include/openssl/core_names.h.in\n21.424  aarch64-linux-g  564195 564175   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.426  sh               564194 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/crmf.h.in > include/openssl/crmf.h\n21.427  touch            564192 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_x509.d.tmp\n21.428  sh               564197 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/crypto.h.in > include/openssl/crypto.h\n21.429  sh               564198 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/ct.h.in > include/openssl/ct.h\n21.432  perl             564199 564190   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha512-armv8.S\n21.433  sh               564203 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/liba\n21.434  sh               564204 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/err.h.in > include/openssl/err.h\n21.435  perl             564200 564197   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/crypto.h.in\n21.436  cmp              564206 564203   0 /usr/bin/cmp apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d\n21.438  perl             564201 564198   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/ct.h.in\n21.439  perl             564207 564204   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/err.h.in\n21.440  perl             564205 564194   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/crmf.h.in\n21.443  mv               564202 564160   0 /usr/bin/mv apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d\n21.443  mv               564208 564203   0 /usr/bin/mv apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d\n21.449  cc1              564209 564195   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_ige.d -MF crypto/aes/libcrypto-lib-aes_ige.d.tmp -MQ crypto/aes/libcrypto-lib-aes_ige.o -D_REENTRANT -D ...\n21.455  sh               564210 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.460  aarch64-linux-g  564211 564210   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.465  sh               564212 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/ess.h.in > include/openssl/ess.h\n21.466  sh               564213 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.467  as               564214 564154   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_cbc.o /tmp/ccCWH1HR.s\n21.469  cc1              564216 564211   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_misc.d -MF crypto/aes/libcrypto-lib-aes_misc.d.tmp -MQ crypto/aes/libcrypto-lib-aes_misc.o -D_REENTRANT -D ...\n21.470  perl             564215 564212   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/ess.h.in\n21.478  aarch64-linux-g  564217 564213   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.481  sh               564218 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/fipskey.h.in > include/openssl/fipskey.h\n21.485  cc1              564220 564217   0 \n21.485  perl             564219 564218   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/fipskey.h.in\n21.497  as               564221 564159   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_cfb.o /tmp/ccubFsie.s\n21.508  touch            564222 564020   0 /usr/bin/touch crypto/aes/libcrypto-lib-aes_cbc.d.tmp\n21.514  sh               564223 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.517  aarch64-linux-g  564224 564223   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.520  sh               564225 564020   0 /bin/sh -c if cmp crypto/aes/libcrypto-lib-aes_cbc.d.tmp crypto/aes/libcrypto-lib-aes_cbc.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n21.529  cc1              564228 564224   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_wrap.d -MF crypto/aes/libcrypto-lib-aes_wrap.d.tmp -MQ crypto/aes/libcrypto-lib-aes_wrap.o -D_REENTRANT -D ...\n21.529  cmp              564227 564225   0 /usr/bin/cmp crypto/aes/libcrypto-lib-aes_cbc.d.tmp crypto/aes/libcrypto-lib-aes_cbc.d\n21.529  as               564226 564172   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_ecb.o /tmp/ccpb1jgf.s\n21.529  mv               564230 564225   0 \n21.529  sh               564229 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aesv8-armx.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/includ\n21.534  perl             564231 564229   0 /usr/bin/perl crypto/aes/asm/aesv8-armx.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.539  touch            564232 564020   0 /usr/bin/touch crypto/aes/libcrypto-lib-aes_cfb.d.tmp\n21.539  sh               564233 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/bsaes-armv8.pl \"linux64\" -I. -Iinclude -Iproviders/common/include -Iprov\n21.546  perl             564234 564233   0 /usr/bin/perl crypto/aes/asm/bsaes-armv8.pl linux64 -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC ...\n21.548  sh               564236 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/lhash.h.in > include/openssl/lhash.h\n21.553  perl             564237 564236   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/lhash.h.in\n21.553  sh               564235 564020   0 /bin/sh -c if cmp crypto/aes/libcrypto-lib-aes_cfb.d.tmp crypto/aes/libcrypto-lib-aes_cfb.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n21.560  sh               564239 564234   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/bsaes-armv8.S\n"
}
```

#### Record 32

```json
{
  "argv": [
    "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
  "pid": 556769,
  "ppid": 555761,
  "root_cargo_pid": 555761,
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

#### Record 33

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556775,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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

#### Record 34

```json
{
  "argv": [
    "/target/debug/build/num-traits-381059396003c1df/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
  "pid": 556777,
  "ppid": 555761,
  "root_cargo_pid": 555761,
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

#### Record 35

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556781,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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

#### Record 36

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556788,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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

#### Record 37

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556824,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556854,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556851,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556960,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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

#### Record 41

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557041,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 557044,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
  "pid": 557044,
  "ppid": 555761,
  "root_cargo_pid": 555761,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_build_script_out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out"
}
```

#### Record 43

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 557044,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557051,
  "ppid": 557044,
  "root_cargo_pid": 555761,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "_build_script_out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557079,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557110,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557184,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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

#### Record 48

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

#### Record 49

```json
{
  "crate": "rustfft",
  "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "event_id": "bsrun:1026f0adb1b65ac3:ffaac7c3e4ef67e2:e1f030fe76560b4d",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
  "out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
  "success": true,
  "target": null,
  "version": "6.2.0",
  "_owner": {
    "crate": "rustfft",
    "version": "6.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 50

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556775,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556781,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "--crate-name",
    "probe0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556788,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556824,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "probe1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556769,
  "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556854,
  "ppid": 556769,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556851,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "probe2",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 556960,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "probe3",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557041,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "--verbose",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 557044,
  "build_script_target_dir": "rustfft-df5ef03d367a47e7",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557051,
  "ppid": 557044,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557079,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557110,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 556777,
  "build_script_target_dir": "num-traits-381059396003c1df",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 557184,
  "ppid": 556777,
  "root_cargo_pid": 555761,
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
  "time": "2026-07-14T02:06:32.036455+00:00",
  "crate": "rustfft",
  "version": "6.2.0",
  "architecture": "ppc64le",
  "duration_seconds": 29.929734781384468,
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "manifest_path": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0"
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
          "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
          "name": "rustfft",
          "version": "6.2.0",
          "manifest_path": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0"
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
      "pid": 556637,
      "ppid": 556517,
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
      "event_id": "used:cc:951da16589636ef0:5e628c6a67b5b31a:0525545e6d709c1c",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb",
      "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
      "pid": 556637,
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
      "pid": 556637,
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
      "pid": 556637,
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.build_script_build.47ce9972ef65bfcd-cgu.0.rcgu.o",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build_script_build-57adbb2bbd7fd3cb.1ucusdkf5nuofdmr0oau77kby.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
      "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-integer-0.1.45",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 556637,
      "ppid": 556517,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk",
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb",
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
          "directory": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk",
          "kind": "object",
          "path": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/rustcuIUtpk/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-556637-1783994771562061943.map",
      "pid": 556637,
      "ppid": 556517,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-556637-1783994771562061943.map"
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
      "pid": 556618,
      "ppid": 556514,
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
      "event_id": "used:cc:10dd48d5a331e0dc:410a9663599996b8:817d5ec450636eb3",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df",
      "path": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
      "pid": 556618,
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
      "pid": 556618,
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
      "pid": 556618,
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.build_script_build.98f2992d73c8cc45-cgu.0.rcgu.o",
        "/target/debug/build/num-traits-381059396003c1df/build_script_build-381059396003c1df.5b9gf293xo1w0d0gwh568vpka.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
      "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.15",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 556618,
      "ppid": 556514,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/raw-dylibs",
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
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN",
        "/target/debug/build/num-traits-381059396003c1df",
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
          "directory": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN",
          "kind": "object",
          "path": "/target/debug/build/num-traits-381059396003c1df/rustcgvmeaN/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-556618-1783994771550927698.map",
      "pid": 556618,
      "ppid": 556514,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-556618-1783994771550927698.map"
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
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 556879,
      "ppid": 556786,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:d5bdbff580f3ec2d:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
      "pid": 556879,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:d41122c6b703436e:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "5e3a58140e55fdc78e2ecc094f666f1f4a376c7cde8b76557cf85cb2f6473bbf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:84a0ffdce8366495:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "46aa930f953b5c3f4fa1ed88441d8391763e733bb68efd7638c24b9287907254",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:854685fd4fba8c4d:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "c37d07b10f9c15732555518c429eb3a5be5e5c1dbeeacc4071165731e8dac99d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:4bab106b4e3573fa:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "e067560a47a2aa50be5a87f5f296643f8fdc22552ca95cb60472a5e1969762dd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:dc4e43c0e8097113:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "2f654a8ad2c98efcefb4b9b10f8a7a795c4924c84004ef06bb0461acd515b7b7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:a1e68d0afed22211:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "dfedc8068cdc89f034b7988a0200317332c9fc9ef322c69b9972eb1f500fb219",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:eaaadfb4582987d8:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "28e866d181d0de30ed4116926c545b5bde1a306adc8b0c6f45010597a8643a2d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:8677398710c6ba0b:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "2eed0991c8065ea577187aaaf6811a0667390482934ca2ae5c9d1499529dba30",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "used:cc:13de6f15aa0d131c:a081759979fc4c6b:e1e632a3f7f81507",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7",
      "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
      "pid": 556879,
      "sha256": "197f2b51d1e298fd95726267e40617336337134065147c3068f766b3fd604153",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "cargo_pkg_name": "rustfft",
      "cargo_pkg_version": "6.2.0",
      "context_path": "/tmp/native-trace-555476-1783994768050/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-555476-1783994768050/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 556879,
      "ppid": 556786,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
        "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/raw-dylibs",
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
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
        "/target/debug/build/rustfft-df5ef03d367a47e7",
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
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/rustcRrZFx8/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.206z3p1wl87v7f58e5wl682iw.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.3lbevgpse88ckmpypvpvt9hdh.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.46eatzjdofbanispp8u4r5m1o.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.6lms4mr6kw2oqnsl939vg87vs.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.7kp1q9z5stu3tb3371jm8ol37.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.a3y76znc7yog9e6gj6gyzobkc.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.d5vcsck29t50yvd2hfcp8rzea.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.f0tadygf8qgaw5s17y06jssvu.0xnee1k.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/rustfft-df5ef03d367a47e7",
          "kind": "object",
          "path": "/target/debug/build/rustfft-df5ef03d367a47e7/build_script_build-df5ef03d367a47e7.2lv715q5bu3rqmozf7aunsi9j.0xnee1k.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-556879-1783994771836987197.map",
      "pid": 556879,
      "ppid": 556786,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-556879-1783994771836987197.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
      "parsed_event_count": 2037,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 2038,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "L::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.276  sh               563925 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.280  perl             563926 563925   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kdfs/x942kdf.c.in\n20.280  perl             563927 563924   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kdfs/tls1_prf.c.in\n20.293  sh               563928 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.299  perl             563929 563928   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ec_kem.c.in\n20.310  sh               563930 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.314  perl             563931 563930   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ecx_kem.c.in\n20.316  sh               563932 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.318  perl             563933 563932   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/ml_kem_kem.c.in\n20.322  sh               563934 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.324  sh               563936 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.324  perl             563935 563934   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/kem/rsa_kem.c.in\n20.330  perl             563937 563936   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ecx_kmgmt.c.in\n20.331  sh               563938 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.334  sh               563939 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.334  perl             563940 563938   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/lms_kmgmt.c.in\n20.339  perl             563941 563939   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ml_dsa_kmgmt.c.in\n20.342  sh               563942 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.346  sh               563944 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.348  perl             563943 563942   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/ml_kem_kmgmt.c.in\n20.351  perl             563945 563944   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/mlx_kmgmt.c.in\n20.361  sh               563946 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.363  perl             563947 563946   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/slh_dsa_kmgmt.c.in\n20.369  sh               563948 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.374  perl             563949 563948   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/keymgmt/template_kmgmt.c.in\n20.421  sh               563950 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.424  sh               563952 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.424  perl             563951 563950   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/cmac_prov.c.in\n20.428  perl             563953 563952   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/gmac_prov.c.in\n20.432  sh               563954 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.436  perl             563955 563954   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/hmac_prov.c.in\n20.451  sh               563956 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.454  sh               563958 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.455  perl             563957 563956   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/kmac_prov.c.in\n20.459  sh               563959 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.461  perl             563960 563958   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/poly1305_prov.c.in\n20.465  perl             563961 563959   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/macs/siphash_prov.c.in\n20.465  sh               563962 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.470  perl             563963 563962   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_ctr.c.in\n20.471  sh               563964 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.473  perl             563965 563964   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_hash.c.in\n20.475  sh               563966 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.476  perl             563967 563966   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/drbg_hmac.c.in\n20.479  sh               563968 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.482  perl             563969 563968   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/fips_crng_test.c.in\n20.484  sh               563970 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.487  perl             563971 563970   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/seed_src.c.in\n20.492  sh               563972 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.496  perl             563973 563972   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/seed_src_jitter.c.in\n20.508  sh               563974 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.512  perl             563975 563974   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/rands/test_rng.c.in\n20.516  sh               563976 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.521  perl             563977 563976   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/dsa_sig.c.in\n20.537  sh               563978 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.541  perl             563979 563978   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/ecdsa_sig.c.in\n20.572  sh               563980 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.575  perl             563981 563980   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/eddsa_sig.c.in\n20.581  sh               563982 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.583  perl             563983 563982   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/ml_dsa_sig.c.in\n20.591  sh               563984 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.593  sh               563985 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.595  perl             563986 563985   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/slh_dsa_sig.c.in\n20.599  sh               563987 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.602  perl             563988 563984   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/rsa_sig.c.in\n20.605  perl             563989 563987   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/signature/sm2_sig.c.in\n20.620  sh               563990 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.623  perl             563991 563990   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/skeymgmt/generic.c.in\n20.625  sh               563992 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.630  perl             563993 563992   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/file_store.c.in\n20.631  sh               563994 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.633  sh               563995 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" providers/implementations\n20.636  perl             563997 563995   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/winstore_store.c.in\n20.636  perl             563996 563994   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile providers/implementations/storemgmt/file_store_any2obj.c.in\n20.641  sh               563998 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfig.cmake.in > OpenSSLC\n20.644  sh               563999 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfig.cmake.in > export\n20.647  perl             564001 563999   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfig.cmake.in\n20.647  perl             564000 563998   0 /usr/bin/perl -I. -Mconfigdata -Mbuilddata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfig.cmake.in\n20.671  sh               564002 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/libcrypto.pc.in > exporter\n20.675  perl             564003 564002   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/libcrypto.pc.in\n20.675  sh               564004 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/libssl.pc.in > exporters/l\n20.681  perl             564005 564004   0 /usr/bin/perl -I. -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/libssl.pc.in\n20.682  sh               564006 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mbuilddata\" \"-Mbuilddata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-config/\n20.685  perl             564007 564006   0 /usr/bin/perl -I. -Mconfigdata -Mbuilddata -Mbuilddata -Mbuilddata util/dofile.pl -oMakefile exporters/pkg-config/openssl.pc.in\n20.772  sh               564008 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Mbuilddata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfigVersi\n20.774  perl             564009 564008   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Mbuilddata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfigVersion.cmake.in\n20.777  sh               564010 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/cmake/OpenSSLConfigVer\n20.778  perl             564011 564010   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/cmake/OpenSSLConfigVersion.cmake.in\n20.800  sh               564012 563792   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Mconfigdata\" \"-Minstalldata\" \"util/dofile.pl\" \"-oMakefile\" exporters/pkg-con\n20.801  perl             564013 564012   0 /usr/bin/perl -I. -Mconfigdata -Mconfigdata -Mconfigdata -Minstalldata util/dofile.pl -oMakefile exporters/pkg-config/openssl.pc.in\n20.865  sh               564014 563792   0 /bin/sh -c \"/usr/bin/make\" depend && \"/usr/bin/make\" _build_libs\n20.866  make             564015 564014   0 /usr/bin/make depend\n20.883  sh               564016 564015   0 /bin/sh -c : \n20.885  sh               564017 564015   0 /bin/sh -c /usr/bin/perl ./util/add-depends.pl \"gcc\"\n20.887  perl             564018 564017   0 /usr/bin/perl ./util/add-depends.pl gcc\n20.951  sh               564019 564015   0 /bin/sh -c : \n20.953  make             564020 564014   0 /usr/bin/make _build_libs\n20.969  sh               564021 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.969  sh               564022 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.972  sh               564023 564020   0 \n20.972  aarch64-linux-g  564027 564023   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.972  aarch64-linux-g  564024 564021   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.972  aarch64-linux-g  564025 564022   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.973  sh               564026 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.975  cc1              564028 564024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_libctx.d -MF apps/lib/libapps-lib-app_libctx.d.tmp -MQ apps/lib/libapps-lib-app_libctx.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.975  aarch64-linux-g  564030 564026   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.975  sh               564029 564020   0 \n20.977  sh               564032 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.977  aarch64-linux-g  564031 564029   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.977  sh               564034 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.977  cc1              564033 564030   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_rand.d -MF apps/lib/libapps-lib-app_rand.d.tmp -MQ apps/lib/libapps-lib-app_rand.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.980  sh               564036 564020   0 \n20.980  cc1              564035 564025   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_params.d -MF apps/lib/libapps-lib-app_params.d.tmp -MQ apps/lib/libapps-lib-app_params.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.980  aarch64-linux-g  564039 564034   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.983  aarch64-linux-g  564037 564032   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.984  sh               564038 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.986  aarch64-linux-g  564040 564036   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.986  cc1              564042 564031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_x509.d -MF apps/lib/libapps-lib-app_x509.d.tmp -MQ apps/lib/libapps-lib-app_x509.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.987  cc1              564041 564027   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-app_provider.d -MF apps/lib/libapps-lib-app_provider.d.tmp -MQ apps/lib/libapps-lib-app_provider.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.987  sh               564044 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n20.989  cc1              564043 564039   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps_opt_printf.d -MF apps/lib/libapps-lib-apps_opt_printf.d.tmp -MQ apps/lib/libapps-lib-apps_opt_printf.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.991  cc1              564047 564037   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps.d -MF apps/lib/libapps-lib-apps.d.tmp -MQ apps/lib/libapps-lib-apps.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.995  cc1              564048 564040   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-apps_ui.d -MF apps/lib/libapps-lib-apps_ui.d.tmp -MQ apps/lib/libapps-lib-apps_ui.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n20.997  aarch64-linux-g  564045 564044   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n20.997  aarch64-linux-g  564049 564038   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.000  sh               564046 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.000  cc1              564050 564049   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-columns.d -MF apps/lib/libapps-lib-columns.d.tmp -MQ apps/lib/libapps-lib-columns.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.004  aarch64-linux-g  564051 564046   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.004  sh               564052 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.006  cc1              564053 564045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-engine.d -MF apps/lib/libapps-lib-engine.d.tmp -MQ apps/lib/libapps-lib-engine.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.007  sh               564055 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.008  aarch64-linux-g  564054 564052   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.009  cc1              564056 564051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-engine_loader.d -MF apps/lib/libapps-lib-engine_loader.d.tmp -MQ apps/lib/libapps-lib-engine_loader.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.010  aarch64-linux-g  564058 564055   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.012  sh               564057 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.015  aarch64-linux-g  564061 564057   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.015  sh               564060 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.017  cc1              564059 564054   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-fmt.d -MF apps/lib/libapps-lib-fmt.d.tmp -MQ apps/lib/libapps-lib-fmt.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.019  aarch64-linux-g  564063 564060   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.022  cc1              564065 564061   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-log.d -MF apps/lib/libapps-lib-log.d.tmp -MQ apps/lib/libapps-lib-log.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.022  cc1              564064 564058   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-http_server.d -MF apps/lib/libapps-lib-http_server.d.tmp -MQ apps/lib/libapps-lib-http_server.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.024  cc1              564066 564063   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-names.d -MF apps/lib/libapps-lib-names.d.tmp -MQ apps/lib/libapps-lib-names.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.027  sh               564062 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.032  aarch64-linux-g  564067 564062   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.040  cc1              564068 564067   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-opt.d -MF apps/lib/libapps-lib-opt.d.tmp -MQ apps/lib/libapps-lib-opt.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.050  as               564069 564054   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-fmt.o /tmp/ccaDaPuj.s\n21.079  touch            564070 564020   0 /usr/bin/touch apps/lib/libapps-lib-fmt.d.tmp\n21.085  sh               564071 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-lib-fm\n21.088  cmp              564072 564071   0 /usr/bin/cmp apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d\n21.094  mv               564073 564071   0 /usr/bin/mv apps/lib/libapps-lib-fmt.d.tmp apps/lib/libapps-lib-fmt.d\n21.102  sh               564074 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.106  aarch64-linux-g  564075 564074   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.110  as               564076 564063   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-names.o /tmp/ccY8EL8X.s\n21.114  cc1              564077 564075   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-s_cb.d -MF apps/lib/libapps-lib-s_cb.d.tmp -MQ apps/lib/libapps-lib-s_cb.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.130  touch            564078 564020   0 /usr/bin/touch apps/lib/libapps-lib-names.d.tmp\n21.131  sh               564079 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-li\n21.133  cmp              564080 564079   0 /usr/bin/cmp apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d\n21.134  mv               564081 564079   0 /usr/bin/mv apps/lib/libapps-lib-names.d.tmp apps/lib/libapps-lib-names.d\n21.137  sh               564082 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.139  aarch64-linux-g  564083 564082   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.142  cc1              564084 564083   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-s_socket.d -MF apps/lib/libapps-lib-s_socket.d.tmp -MQ apps/lib/libapps-lib-s_socket.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.160  as               564085 564039   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-apps_opt_printf.o /tmp/ccOTBCSc.s\n21.169  make             564086 563057   0 /tmp/native-trace-559618-1783994778377/shims/make depend\n21.171  make             564087 564086   0 /usr/bin/make depend\n21.181  touch            564088 564020   0 /usr/bin/touch apps/lib/libapps-lib-apps_opt_printf.d.tmp\n21.184  sh               564089 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d > /dev/null 2> /dev/null; then \\\\n\trm -f\n21.191  cmp              564090 564089   0 /usr/bin/cmp apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d\n21.195  mv               564091 564089   0 /usr/bin/mv apps/lib/libapps-lib-apps_opt_printf.d.tmp apps/lib/libapps-lib-apps_opt_printf.d\n21.200  sh               564092 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iapps/include  -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-s\n21.204  sh               564094 564087   0 /bin/sh -c : \n21.207  aarch64-linux-g  564093 564092   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iapps/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC -DOPENSSLDIR=\"/usr/local/ssl\" -DENGINESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/engines-3 -DMODULESDIR=\"/target/aarch64-unknown-linux-gnu/debug/build/openssl-sys-72ff966b8023ad79/out/openssl-build/install/lib/ossl-modu ...\n21.207  sh               564095 564087   0 /bin/sh -c /usr/bin/perl ./util/add-depends.pl \"gcc\"\n21.210  perl             564096 564095   0 /usr/bin/perl ./util/add-depends.pl gcc\n21.213  cc1              564097 564093   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I apps/include -imultiarch aarch64-linux-gnu -MMD apps/lib/libapps-lib-tlssrp_depr.d -MF apps/lib/libapps-lib-tlssrp_depr.d.tmp -MQ apps/lib/libapps-lib-tlssrp_depr.o -D_REENTRANT -D OPENSSL_USE_NODELETE -D ...\n21.229  as               564098 564030   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_rand.o /tmp/cc7mOhTv.s\n21.239  as               564099 564061   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-log.o /tmp/cc5St0oR.s\n21.252  touch            564100 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_rand.d.tmp\n21.256  sh               564101 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/liba\n21.258  as               564102 564049   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-columns.o /tmp/ccJSc3YX.s\n21.262  cmp              564103 564101   0 /usr/bin/cmp apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d\n21.264  as               564105 564051   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-engine_loader.o /tmp/ccXgwcY4.s\n21.267  touch            564104 564020   0 /usr/bin/touch apps/lib/libapps-lib-log.d.tmp\n21.267  mv               564106 564101   0 /usr/bin/mv apps/lib/libapps-lib-app_rand.d.tmp apps/lib/libapps-lib-app_rand.d\n21.270  as               564107 564040   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-apps_ui.o /tmp/cclosUzh.s\n21.271  sh               564108 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-lib-lo\n21.274  as               564109 564024   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_libctx.o /tmp/ccGeSkj2.s\n21.276  cmp              564110 564108   0 /usr/bin/cmp apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d\n21.281  mv               564111 564108   0 /usr/bin/mv apps/lib/libapps-lib-log.d.tmp apps/lib/libapps-lib-log.d\n21.282  sh               564112 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha1-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/in\n21.283  as               564113 564045   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-engine.o /tmp/ccMZ62SF.s\n21.287  perl             564114 564112   0 /usr/bin/perl crypto/aes/asm/aes-sha1-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.292  touch            564115 564020   0 /usr/bin/touch apps/lib/libapps-lib-columns.d.tmp\n21.295  sh               564116 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapp\n21.299  as               564118 564025   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_params.o /tmp/ccKVxgG7.s\n21.301  cmp              564117 564116   0 /usr/bin/cmp apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d\n21.301  as               564119 564027   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_provider.o /tmp/cc4Yc4xf.s\n21.303  mv               564120 564116   0 /usr/bin/mv apps/lib/libapps-lib-columns.d.tmp apps/lib/libapps-lib-columns.d\n21.307  sh               564121 564114   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha1-armv8.S\"\n21.309  sh               564122 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha256-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/\n21.313  perl             564124 564122   0 /usr/bin/perl crypto/aes/asm/aes-sha256-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.313  perl             564125 564121   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha1-armv8.S\n21.316  touch            564123 564020   0 /usr/bin/touch apps/lib/libapps-lib-apps_ui.d.tmp\n21.320  touch            564126 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_libctx.d.tmp\n21.323  touch            564127 564020   0 /usr/bin/touch apps/lib/libapps-lib-engine.d.tmp\n21.326  touch            564128 564020   0 /usr/bin/touch apps/lib/libapps-lib-engine_loader.d.tmp\n21.328  sh               564129 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapp\n21.331  sh               564131 564087   0 /bin/sh -c : \n21.333  touch            564130 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_provider.d.tmp\n21.334  cmp              564132 564129   0 /usr/bin/cmp apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d\n21.335  mv               564134 564129   0 /usr/bin/mv apps/lib/libapps-lib-apps_ui.d.tmp apps/lib/libapps-lib-apps_ui.d\n21.338  sh               564133 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/\n21.340  make             564137 564136   0 /usr/bin/make build_libs\n21.340  make             564136 563057   0 /tmp/native-trace-559618-1783994778377/shims/make build_libs\n21.340  sh               564135 564124   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha256-armv8.S\"\n21.342  perl             564138 564135   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha256-armv8.S\n21.345  sh               564139 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/libapps-\n21.347  sh               564141 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d > /dev/null 2> /dev/null; then \\\\n\trm -f app\n21.349  cmp              564140 564133   0 /usr/bin/cmp apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d\n21.349  cmp              564142 564139   0 /usr/bin/cmp apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d\n21.350  sh               564143 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/\n21.353  cmp              564145 564141   0 /usr/bin/cmp apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d\n21.353  as               564146 564031   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I apps/include -EL -mabi=lp64 --noexecstack -o apps/lib/libapps-lib-app_x509.o /tmp/ccEZcLyB.s\n21.354  cmp              564144 564143   0 /usr/bin/cmp apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d\n21.356  mv               564147 564141   0 /usr/bin/mv apps/lib/libapps-lib-engine_loader.d.tmp apps/lib/libapps-lib-engine_loader.d\n21.360  mv               564148 564133   0 /usr/bin/mv apps/lib/libapps-lib-app_libctx.d.tmp apps/lib/libapps-lib-app_libctx.d\n21.360  sh               564149 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aes-sha512-armv8.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/\n21.361  sh               564152 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.362  mv               564150 564143   0 /usr/bin/mv apps/lib/libapps-lib-app_provider.d.tmp apps/lib/libapps-lib-app_provider.d\n21.365  mv               564151 564139   0 /usr/bin/mv apps/lib/libapps-lib-engine.d.tmp apps/lib/libapps-lib-engine.d\n21.367  aarch64-linux-g  564154 564152   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.369  touch            564153 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_params.d.tmp\n21.371  cc1              564155 564154   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_cbc.d -MF crypto/aes/libcrypto-lib-aes_cbc.d.tmp -MQ crypto/aes/libcrypto-lib-aes_cbc.o -D_REENTRANT -D ...\n21.372  sh               564156 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.374  sh               564160 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/\n21.375  perl             564157 564149   0 /usr/bin/perl crypto/aes/asm/aes-sha512-armv8.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.375  sh               564161 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.376  sh               564158 564137   0 /bin/sh -c /usr/bin/perl util/mkinstallvars.pl COMMENT=\"This file should be used when building against this OpenSSL build, and should never\n21.376  sh               564162 564137   0 /bin/sh -c /usr/bin/perl util/mkinstallvars.pl \"PREFIX=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/o\n21.378  perl             564164 564162   0 /usr/bin/perl util/mkinstallvars.pl PREFIX=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install BINDIR=bin LIBDIR=lib libdir=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib INCLUDEDIR=include APPLINKDIR=include/openssl ENGINESDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/engines- MODULESDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/ossl-mod PKGCONFIGDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/pkgcon CMAKECONFIGDIR=/target/powerpc64le-unknown-linux-gnu/debug/build/openssl-sys-6ad95f5afc884b4a/out/openssl-build/install/lib/cmak LDLIBS=-ldl -pthread  VERSION=3.6.3\n21.380  sh               564167 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.380  sh               564166 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/crypto/bn_conf.h.in > include/crypto/bn_conf.h\n21.381  aarch64-linux-g  564159 564156   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.382  perl             564168 564166   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/crypto/bn_conf.h.in\n21.382  sh               564169 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/crypto/dso_conf.h.in > include/crypto/dso_conf.h\n21.383  perl             564165 564158   0 /usr/bin/perl util/mkinstallvars.pl COMMENT=This file should be used when building against this OpenSSL build, and should never be installed PREFIX=. BINDIR=apps APPLINKDIR=ms LIBDIR= INCLUDEDIR=include INCLUDEDIR=./include ENGINESDIR=engines MODULESDIR=providers VERSION=3.6.3 LDLIBS=-ldl -pthread \n21.383  sh               564170 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/asn1.h.in > include/openssl/asn1.h\n21.384  aarch64-linux-g  564172 564167   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.386  perl             564173 564170   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/asn1.h.in\n21.386  perl             564171 564169   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/crypto/dso_conf.h.in\n21.390  sh               564174 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/asn1t.h.in > include/openssl/asn1t.h\n21.391  sh               564177 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/bio.h.in > include/openssl/bio.h\n21.397  perl             564178 564174   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/asn1t.h.in\n21.397  cc1              564182 564172   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_ecb.d -MF crypto/aes/libcrypto-lib-aes_ecb.d.tmp -MQ crypto/aes/libcrypto-lib-aes_ecb.o -D_REENTRANT -D ...\n21.397  aarch64-linux-g  564163 564161   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.403  perl             564180 564177   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/bio.h.in\n21.405  sh               564181 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/cmp.h.in > include/openssl/cmp.h\n21.406  sh               564185 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/cms.h.in > include/openssl/cms.h\n21.406  cc1              564183 564163   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_core.d -MF crypto/aes/libcrypto-lib-aes_core.d.tmp -MQ crypto/aes/libcrypto-lib-aes_core.o -D_REENTRANT -D ...\n21.409  perl             564184 564181   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/cmp.h.in\n21.409  sh               564186 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/comp.h.in > include/openssl/comp.h\n21.411  perl             564188 564186   0 \n21.411  sh               564189 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/conf.h.in > include/openssl/conf.h\n21.412  sh               564175 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.413  perl             564187 564185   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/cms.h.in\n21.416  perl             564191 564189   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/conf.h.in\n21.417  cc1              564179 564159   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_cfb.d -MF crypto/aes/libcrypto-lib-aes_cfb.d.tmp -MQ crypto/aes/libcrypto-lib-aes_cfb.o -D_REENTRANT -D ...\n21.419  sh               564193 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Iutil/perl\" \"-Mconfigdata\" \"-MOpenSSL::paramnames\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/core_name\n21.420  cmp              564176 564160   0 /usr/bin/cmp apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d\n21.422  sh               564190 564157   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 \"crypto/aes/aes-sha512-armv8.S\"\n21.422  perl             564196 564193   0 /usr/bin/perl -I. -Iutil/perl -Mconfigdata -MOpenSSL::paramnames util/dofile.pl -oMakefile include/openssl/core_names.h.in\n21.424  aarch64-linux-g  564195 564175   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.426  sh               564194 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/crmf.h.in > include/openssl/crmf.h\n21.427  touch            564192 564020   0 /usr/bin/touch apps/lib/libapps-lib-app_x509.d.tmp\n21.428  sh               564197 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/crypto.h.in > include/openssl/crypto.h\n21.429  sh               564198 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/ct.h.in > include/openssl/ct.h\n21.432  perl             564199 564190   0 /usr/bin/perl crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/aes-sha512-armv8.S\n21.433  sh               564203 564020   0 /bin/sh -c if cmp apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d > /dev/null 2> /dev/null; then \\\\n\trm -f apps/lib/liba\n21.434  sh               564204 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/err.h.in > include/openssl/err.h\n21.435  perl             564200 564197   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/crypto.h.in\n21.436  cmp              564206 564203   0 /usr/bin/cmp apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d\n21.438  perl             564201 564198   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/ct.h.in\n21.439  perl             564207 564204   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/err.h.in\n21.440  perl             564205 564194   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/crmf.h.in\n21.443  mv               564202 564160   0 /usr/bin/mv apps/lib/libapps-lib-app_params.d.tmp apps/lib/libapps-lib-app_params.d\n21.443  mv               564208 564203   0 /usr/bin/mv apps/lib/libapps-lib-app_x509.d.tmp apps/lib/libapps-lib-app_x509.d\n21.449  cc1              564209 564195   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_ige.d -MF crypto/aes/libcrypto-lib-aes_ige.d.tmp -MQ crypto/aes/libcrypto-lib-aes_ige.o -D_REENTRANT -D ...\n21.455  sh               564210 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.460  aarch64-linux-g  564211 564210   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.465  sh               564212 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/ess.h.in > include/openssl/ess.h\n21.466  sh               564213 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.467  as               564214 564154   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_cbc.o /tmp/ccCWH1HR.s\n21.469  cc1              564216 564211   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_misc.d -MF crypto/aes/libcrypto-lib-aes_misc.d.tmp -MQ crypto/aes/libcrypto-lib-aes_misc.o -D_REENTRANT -D ...\n21.470  perl             564215 564212   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/ess.h.in\n21.478  aarch64-linux-g  564217 564213   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.481  sh               564218 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/fipskey.h.in > include/openssl/fipskey.h\n21.485  cc1              564220 564217   0 \n21.485  perl             564219 564218   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/fipskey.h.in\n21.497  as               564221 564159   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_cfb.o /tmp/ccubFsie.s\n21.508  touch            564222 564020   0 /usr/bin/touch crypto/aes/libcrypto-lib-aes_cbc.d.tmp\n21.514  sh               564223 564020   0 /bin/sh -c aarch64-linux-gnu-gcc  -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include  -DBSAES_ASM -DECP_NISTZ256_\n21.517  aarch64-linux-g  564224 564223   0 /usr/bin/aarch64-linux-gnu-gcc -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -DBSAES_ASM -DECP_NISTZ256_ASM -DECP_SM2P256_ASM -DKECCAK1600_ASM -DMD5_ASM -DOPENSSL_BN_ASM_MONT -DOPENSSL_CPUID_OBJ -DOPENSSL_SM3_ASM -DPOLY1305_ASM -DSHA1_ASM -DSHA256_ASM -DSHA512_ASM -DSM4_ASM -DSTATIC_LEGACY -DVPAES_ASM ...\n21.520  sh               564225 564020   0 /bin/sh -c if cmp crypto/aes/libcrypto-lib-aes_cbc.d.tmp crypto/aes/libcrypto-lib-aes_cbc.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n21.529  cc1              564228 564224   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I . -I include -I providers/common/include -I providers/implementations/include -imultiarch aarch64-linux-gnu -MMD crypto/aes/libcrypto-lib-aes_wrap.d -MF crypto/aes/libcrypto-lib-aes_wrap.d.tmp -MQ crypto/aes/libcrypto-lib-aes_wrap.o -D_REENTRANT -D ...\n21.529  cmp              564227 564225   0 /usr/bin/cmp crypto/aes/libcrypto-lib-aes_cbc.d.tmp crypto/aes/libcrypto-lib-aes_cbc.d\n21.529  as               564226 564172   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I . -I include -I providers/common/include -I providers/implementations/include -EL -mabi=lp64 --noexecstack -o crypto/aes/libcrypto-lib-aes_ecb.o /tmp/ccpb1jgf.s\n21.529  mv               564230 564225   0 \n21.529  sh               564229 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/aesv8-armx.pl \"linux64\" -Icrypto -I. -Iinclude -Iproviders/common/includ\n21.534  perl             564231 564229   0 /usr/bin/perl crypto/aes/asm/aesv8-armx.pl linux64 -Icrypto -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE ...\n21.539  touch            564232 564020   0 /usr/bin/touch crypto/aes/libcrypto-lib-aes_cfb.d.tmp\n21.539  sh               564233 564020   0 /bin/sh -c CC=\"aarch64-linux-gnu-gcc\" /usr/bin/perl crypto/aes/asm/bsaes-armv8.pl \"linux64\" -I. -Iinclude -Iproviders/common/include -Iprov\n21.546  perl             564234 564233   0 /usr/bin/perl crypto/aes/asm/bsaes-armv8.pl linux64 -I. -Iinclude -Iproviders/common/include -Iproviders/implementations/include -fPIC -pthread -Wa,--noexecstack -Wall -O3 -O2 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -DOPENSSL_USE_NODELETE -DOPENSSL_PIC ...\n21.548  sh               564236 564137   0 /bin/sh -c /usr/bin/perl \"-I.\" \"-Mconfigdata\" \"util/dofile.pl\" \"-oMakefile\" include/openssl/lhash.h.in > include/openssl/lhash.h\n21.553  perl             564237 564236   0 /usr/bin/perl -I. -Mconfigdata util/dofile.pl -oMakefile include/openssl/lhash.h.in\n21.553  sh               564235 564020   0 /bin/sh -c if cmp crypto/aes/libcrypto-lib-aes_cfb.d.tmp crypto/aes/libcrypto-lib-aes_cfb.d > /dev/null 2> /dev/null; then \\\\n\trm -f crypto/\n21.560  sh               564239 564234   0 /bin/sh -c \"/usr/bin/perl\" crypto/aes/asm/../../perlasm/arm-xlate.pl linux64 crypto/aes/bsaes-armv8.S\n"
    },
    {
      "argv": [
        "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-integer-57adbb2bbd7fd3cb/build-script-build",
      "pid": 556769,
      "ppid": 555761,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556775,
      "ppid": 556769,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/num-traits-381059396003c1df/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-traits-381059396003c1df/build-script-build",
      "pid": 556777,
      "ppid": 555761,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556781,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556788,
      "ppid": 556769,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556824,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556854,
      "ppid": 556769,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556851,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe2",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556960,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe3",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557041,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 557044,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
      "pid": 557044,
      "ppid": 555761,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--verbose",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 557044,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557051,
      "ppid": 557044,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe4",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557079,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe5",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557110,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "probe6",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557184,
      "ppid": 556777,
      "root_cargo_pid": 555761,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
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
    },
    {
      "crate": "rustfft",
      "cwd": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "event_id": "bsrun:1026f0adb1b65ac3:ffaac7c3e4ef67e2:e1f030fe76560b4d",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/rustfft-df5ef03d367a47e7/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
      "out_dir": "/target/debug/build/rustfft-df5ef03d367a47e7/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
      "success": true,
      "target": null,
      "version": "6.2.0",
      "_owner": {
        "crate": "rustfft",
        "version": "6.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0#rustfft@6.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-m31lino4/src/rustfft-6.2.0",
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
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556775,
      "ppid": 556769,
      "root_cargo_pid": 555761,
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
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556781,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556788,
      "ppid": 556769,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556824,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-integer-5f73e8065254593f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556769,
      "build_script_target_dir": "num-integer-57adbb2bbd7fd3cb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556854,
      "ppid": 556769,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556851,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 556960,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557041,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
      "build_script_root_pid": 557044,
      "build_script_target_dir": "rustfft-df5ef03d367a47e7",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557051,
      "ppid": 557044,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557079,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557110,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-3da53bf76e2546e3/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 556777,
      "build_script_target_dir": "num-traits-381059396003c1df",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 557184,
      "ppid": 556777,
      "root_cargo_pid": 555761,
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
