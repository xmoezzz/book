# `iana-time-zone-haiku` `0.1.2`

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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
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
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
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
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-35966-1783992729662144795.map",
  "pid": 35966,
  "ppid": 35935,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-35966-1783992729662144795.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a`

Owner: `iana-time-zone-haiku` `0.1.2`

### Source files

* `/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/src/implementation.cc`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-w",
    "-std=c++11",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "-c",
    "src/implementation.cc"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36036,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/implementation.cc",
    "-quiet",
    "-dumpbase",
    "implementation.cc",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-std=c++11",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/implementation.cc",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 36037,
  "ppid": 36036,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "root_cargo_pid": 35203,
  "build_script_root_pid": 36002,
  "build_script_related": true,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
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
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 36047,
  "ppid": 36002,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "root_cargo_pid": 35203,
  "build_script_root_pid": 36002,
  "build_script_related": true,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
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
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "workspace_root": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2"
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
      "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
      "name": "iana-time-zone-haiku",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2"
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
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 35966,
  "ppid": 35935,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:93b1c8a41e0c1747:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
  "pid": 35966,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:a57ee688dea2ebad:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "f6ba4639dd78da0843db0f4da699ac20219599145a5715048cfda8ec8c13ac48",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:7533f27938283283:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "781115f6525dd5d26dda7cd62cd01e88e243d8a6fe6a3803f80672ae951c19cd",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:bbf73d8d643cb22e:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "36be75c7b04edcff9be1edbf6fbde2cf7c075f59e575da8e69c3d2dc57197a42",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:67801784f7cd1f99:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "5082d25a80a7592602ebb812c28a896cd1138e829e00dc3582c9148d1b346e58",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:02ac716efa0d04c1:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "122271cd33d7079bd2151c1ada95f6de38f42b5624ff08ee396cfd50a3463ee5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:1762acc653e69b69:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "2d838150e34cd9d83d4a5e68c624522176227dcefa402747bb326cbdcab84eb6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:0d108f3e63437bf0:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "47596c16fa66dab9fd2c2f18226a30e856c789c868a04c7e094798bd0a046c3e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:a084d9b0fdee2924:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "6e687db2f545eda754147c1ed14d19d14b90ab7de259a3d62595c38fe0e7abc5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:67ea814cca1e7989:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "81976be8710da7c5a4c684015e35bb9c90d242c08c5b2c5eb66a92a946c310d4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:a788200ac155e4f0:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "3c1e348b38b6cac8080c9c2a88001552d34dbc48c43d93334cea8e453ca26df1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:450ee4ef4d804d3f:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "5b86d6de74e5cbaa11b63e8e7daa61ce8f1c1219a94a91f7c4a726d8700eb838",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "used:cc:8494be7927262a0c:b3edb36256782ef7:27c01d5814576e22",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
  "pid": 35966,
  "sha256": "ad9e70601c6cd44d79945066c13dbf71295e21e37f8b9bd83b09a4541df8ee63",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
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
  "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "cargo_pkg_name": "iana-time-zone-haiku",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-34379-1783992725358/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-34379-1783992725358/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 35966,
  "ppid": 35935,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
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
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
      "kind": "object",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-35966-1783992729662144795.map",
  "pid": 35966,
  "ppid": 35935,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-35966-1783992729662144795.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cargo_manifest_dir"
  }
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

#### Record 20

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 570,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 571,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "       37356  37351    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.185   collect2         37357  37356    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.187   ld.lld           37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n5.189   rust-lld         37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.222   cc               37380  37325    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.223   cc               37381  37327    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.223   cc               37382  37380    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.226   cc               37383  37381    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.227   collect2         37385  37382    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.228   collect2         37386  37383    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.230   ld.lld           37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n5.230   ld.lld           37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n5.232   rust-lld         37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.233   rust-lld         37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.245   build-script-bu  37393  37290    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n5.256   cc               37423  37321    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.258   cc               37424  37423    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.262   collect2         37425  37424    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.264   ld.lld           37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n5.267   rust-lld         37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.280   build-script-bu  37444  37290    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n5.283   build-script-bu  37446  37290    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n5.298   cargo            37447  36863    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n5.309   build-script-bu  37449  37290    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n5.313   rustc            37450  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n5.315   rustc            37452  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.341   rustc            37465  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.341   rustc            37464  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.342   rustc            37467  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=cbc0344642a3fe61 ...\n5.342   rustc            37466  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.373   cc               37488  37467    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.374   cc               37493  37488    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.378   collect2         37494  37493    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.379   ld.lld           37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n5.381   rust-lld         37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.415   cc               37518  37464    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.416   cc               37519  37466    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.417   cc               37521  37519    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.417   cc               37520  37518    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.420   collect2         37525  37521    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.423   ld.lld           37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n5.423   collect2         37527  37520    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.426   rustc            37526  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.427   ld.lld           37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n5.428   rust-lld         37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.429   rust-lld         37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.435   build-script-bu  37531  37447    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n5.447   cc               37568  37465    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.449   cc               37570  37568    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.453   collect2         37571  37570    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.456   ld.lld           37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n5.458   rust-lld         37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.483   build-script-bu  37590  37447    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n5.487   build-script-bu  37592  37447    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n5.499   build-script-bu  37594  37447    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n5.505   rustc            37596  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.567   rustc            37606  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.567   rustc            37607  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.653   rustc            37621  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=2bb0f49e2ccb2b73 ...\n5.689   rustc            37628  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.714   rustc            37636  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.774   rustc            37646  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c73793a7c0eb3dd6 ...\n5.838   rustc            37653  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.916   rustc            37661  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c16cb3cec9db833d ...\n8.451   sh               38036  2147557   0 /bin/sh -c which ps\n8.452   which            38036  2147557   0 /usr/bin/which ps\n8.455   sh               38037  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.457   ps               38037  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.489   sh               38038  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n8.490   cpuUsage.sh      38038  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n8.492   sed              38039  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.495   cat              38040  38038    0 /usr/bin/cat /proc/2240539/stat\n8.497   cat              38041  38038    0 /usr/bin/cat /proc/4193716/stat\n8.498   sleep            38042  38038    0 /usr/bin/sleep 1\n8.980   runc             38043  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process926607668 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.987   exe              38050  38043    0 /proc/self/exe init\n9.013   etcdctl          38053  38043    0 /usr/local/bin/etcdctl endpoint health\n9.036   16               38070  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n9.039   16               38071  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n9.197   drkonqi-coredum  38071  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 887-38069-0\n9.200   systemd-coredum  38070  1        0 /usr/lib/systemd/systemd-coredump\n9.501   sed              38082  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n9.504   cat              38083  38038    0 /usr/bin/cat /proc/2240539/stat\n9.506   cat              38085  38038    0 /usr/bin/cat /proc/4193716/stat\n9.703   9                38087  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n9.709   abrt-server      38088  1118     0 /usr/bin/abrt-server -s\n9.722   drkonqi-coredum  38087  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n9.738   abrt-handle-eve  38089  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312\n9.755   sh               38092  38089    0 /bin/sh -c abrt-action-save-package-data\\n\n9.757   abrt-action-sav  38092  38089    0 /usr/bin/abrt-action-save-package-data\n9.773   9                38095  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n9.777   plasma_waitforn  38095  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n9.821   sh               38097  38089    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n9.823   cut              38099  38097    0 /usr/bin/cut -d: -f1\n9.823   cat              38100  38098    0 /usr/bin/cat uid\n9.824   getent           38098  38097    0 /usr/bin/getent passwd 1000\n9.826   lscpu            38101  38097    0 /usr/bin/lscpu\n9.843   sh               38102  38089    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n9.845   runlevel         38103  38102    0 /usr/bin/runlevel\n9.857   sh               38104  38089    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n9.859   grep             38105  38104    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n9.861   grep             38106  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n9.863   grep             38107  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n9.865   abrt-action-cor  38108  38104    0 /usr/libexec/abrt-action-coredump -x\n9.932   abrt-action-gen  38109  38104    0 /usr/bin/abrt-action-generate-core-backtrace\n9.990   abrt-action-ana  38110  38104    0 /usr/bin/abrt-action-analyze-vulnerability\n9.993   eu-readelf       38112  38111    0 /usr/bin/eu-readelf -n coredump\n9.993   grep             38113  38111    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n9.993   sed              38114  38111    0 /usr/bin/sed s/[^0-9]//g\n9.997   gdb              38116  38115    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n10.014  iconv            38117  38116    0 /usr/bin/iconv -l\n10.118  abrt-action-ana  38126  38104    0 /usr/bin/abrt-action-analyze-c\n10.132  eu-unstrip       38127  38126    0 /usr/bin/eu-unstrip --core=./coredump -n\n10.152  abrt-action-lis  38128  38104    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n10.217  cat              38130  38129    0 /usr/bin/cat executable\n10.218  cat              38131  38129    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312/uid\n10.220  journalctl       38132  38129    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n10.231  abrt-action-cor  38133  38104    0 /usr/libexec/abrt-action-coredump -r\n10.275  abrt-handle-eve  38134  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.288  sh               38135  38134    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n10.289  dbus-send        38135  38134    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.291  sh               38136  38134    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n10.293  abrt-action-not  38137  38136    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.341  sh               38138  38137    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n10.342  reporter-system  38138  38137    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n12.202  16               38141  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n12.219  frpc             38141  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.786  runc             38147  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup kill --all 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 9\n17.806  runc             38153  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup delete 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n18.006  containerd-shim  38159  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 delete\n18.009  runc             38166  38159    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d109 --log-format json delete --force 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n18.058  sh               38176  38172    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc807bb6\n18.059  ethtool          38177  38176    0 /usr/sbin/ethtool -i vethc807bb6\n18.060  sed              38178  38176    0 /usr/bin/sed -n s/^driver: //p\n18.067  systemd-sysctl   38181  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc807bb6 --prefix=/net/ipv4/neigh/vethc807bb6 --prefix=/net/ipv6/conf/vethc807bb6 --prefix=/net/ipv6/neigh/vethc807bb6\n18.266  runc             38183  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup kill --all 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 9\n18.286  runc             38189  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup delete 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n18.491  containerd-shim  38195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a delete\n18.494  runc             38202  38195    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f8 --log-format json delete --force 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n18.533  systemd-sysctl   38207  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth31a3e53 --prefix=/net/ipv4/neigh/veth31a3e53 --prefix=/net/ipv6/conf/veth31a3e53 --prefix=/net/ipv6/neigh/veth31a3e53\n18.558  runc             38209  33897    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 --log-format json --systemd-cgroup kill --all 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3 9\n18.570  rustup           38215  32637    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.577  runc             38224  33897    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 --log-format json --systemd-cgroup delete 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3\n18.772  sh               38230  2147557   0 /bin/sh -c which ps\n18.774  which            38230  2147557   0 /usr/bin/which ps\n18.776  sh               38231  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.778  ps               38231  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.791  containerd-shim  38232  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 delete\n18.794  runc             38238  38232    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a --log-format json delete --force 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3\n18.810  sh               38244  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.811  cpuUsage.sh      38244  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.813  sed              38245  38244    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.816  cat              38246  38244    0 /usr/bin/cat /proc/2240539/stat\n18.817  cat              38247  38244    0 /usr/bin/cat /proc/4193716/stat\n18.819  sleep            38248  38244    0 /usr/bin/sleep 1\n18.833  systemd-sysctl   38249  38208    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth597109a --prefix=/net/ipv4/neigh/veth597109a --prefix=/net/ipv6/conf/veth597109a --prefix=/net/ipv6/neigh/veth597109a\n"
}
```

#### Record 21

```json
{
  "argv": [
    "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build",
  "pid": 36002,
  "ppid": 35203,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out"
}
```

#### Record 22

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/6863030990727937565detect_compiler_famil"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36004,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 23

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/6863030990727937565detect_compiler_famil",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "pid": 36013,
  "ppid": 36004,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 24

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36014,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 25

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-E",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/12036883374344146994detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36015,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 26

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-E",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/12036883374344146994detect_compiler_fami",
    "-mlittle-endian",
    "-mabi=lp64",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "pid": 36017,
  "ppid": 36015,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 27

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36021,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
    "-c",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36028,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "pid": 36029,
  "ppid": 36028,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
    "/tmp/ccO1Zg0s.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 36031,
  "ppid": 36028,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-w",
    "-std=c++11",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "-c",
    "src/implementation.cc"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-g++",
  "pid": 36036,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/implementation.cc",
    "-quiet",
    "-dumpbase",
    "implementation.cc",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-std=c++11",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "pid": 36037,
  "ppid": 36036,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
    "-W",
    "-EL",
    "-mabi=lp64",
    "-o",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "/tmp/ccOVdRq5.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
  "pid": 36042,
  "ppid": 36036,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 34

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 36047,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "sD",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 36002,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "comm": "aarch64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/aarch64-linux-gnu-ar",
  "pid": 36048,
  "ppid": 36002,
  "root_cargo_pid": 35203,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "crate": "iana-time-zone-haiku",
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "event_id": "bsrun:77bb561715340897:f4c3d0f1165bf29b:091aee4132cd4cef",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 37

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "src": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 36029,
  "ppid": 36028,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "root_cargo_pid": 35203,
  "build_script_root_pid": 36002,
  "build_script_related": true,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "aarch64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/implementation.cc",
    "-quiet",
    "-dumpbase",
    "implementation.cc",
    "-mlittle-endian",
    "-mabi=lp64",
    "-auxbase-strip",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-w",
    "-std=c++11",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/implementation.cc",
  "output": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 36037,
  "ppid": 36036,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "root_cargo_pid": 35203,
  "build_script_root_pid": 36002,
  "build_script_related": true,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 39

```json
{
  "event": "archive",
  "tool": "/usr/bin/aarch64-linux-gnu-ar",
  "real_tool": "/usr/bin/aarch64-linux-gnu-ar",
  "argv": [
    "/usr/bin/aarch64-linux-gnu-ar",
    "cqD",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
  ],
  "archive": "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
  "objects": [
    "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 36047,
  "ppid": 36002,
  "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "root_cargo_pid": 35203,
  "build_script_root_pid": 36002,
  "build_script_related": true,
  "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
  "_owner": {
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
    "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
  "_build_script_out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:32:27.226366+00:00",
  "crate": "iana-time-zone-haiku",
  "version": "0.1.2",
  "architecture": "aarch64",
  "duration_seconds": 24.226509294938296,
  "trace_record_count": 36,
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
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "manifest_path": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 19,
    "unattributed_event_count": 17,
    "owners": [
      {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "event_count": 19,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 13,
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
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "workspace_root": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2"
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
          "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
          "name": "iana-time-zone-haiku",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2"
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
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 35966,
      "ppid": 35935,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:93b1c8a41e0c1747:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
      "pid": 35966,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:a57ee688dea2ebad:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "f6ba4639dd78da0843db0f4da699ac20219599145a5715048cfda8ec8c13ac48",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:7533f27938283283:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "781115f6525dd5d26dda7cd62cd01e88e243d8a6fe6a3803f80672ae951c19cd",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:bbf73d8d643cb22e:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "36be75c7b04edcff9be1edbf6fbde2cf7c075f59e575da8e69c3d2dc57197a42",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:67801784f7cd1f99:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "5082d25a80a7592602ebb812c28a896cd1138e829e00dc3582c9148d1b346e58",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:02ac716efa0d04c1:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "122271cd33d7079bd2151c1ada95f6de38f42b5624ff08ee396cfd50a3463ee5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:1762acc653e69b69:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "2d838150e34cd9d83d4a5e68c624522176227dcefa402747bb326cbdcab84eb6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:0d108f3e63437bf0:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "47596c16fa66dab9fd2c2f18226a30e856c789c868a04c7e094798bd0a046c3e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:a084d9b0fdee2924:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "6e687db2f545eda754147c1ed14d19d14b90ab7de259a3d62595c38fe0e7abc5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:67ea814cca1e7989:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "81976be8710da7c5a4c684015e35bb9c90d242c08c5b2c5eb66a92a946c310d4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:a788200ac155e4f0:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "3c1e348b38b6cac8080c9c2a88001552d34dbc48c43d93334cea8e453ca26df1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:450ee4ef4d804d3f:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "5b86d6de74e5cbaa11b63e8e7daa61ce8f1c1219a94a91f7c4a726d8700eb838",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "used:cc:8494be7927262a0c:b3edb36256782ef7:27c01d5814576e22",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
      "pid": 35966,
      "sha256": "ad9e70601c6cd44d79945066c13dbf71295e21e37f8b9bd83b09a4541df8ee63",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
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
      "output": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "cargo_pkg_name": "iana-time-zone-haiku",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-34379-1783992725358/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-34379-1783992725358/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 35966,
      "ppid": 35935,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
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
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/rustcx36aVT/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.3j8blf158c2htoq6xqb01mjo0.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4he2cu1c8el2g61g5nm9cr0xq.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.4jxfys394mjjd0ap72vj6i623.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6my3j1dswa6x50qiwbikn76vl.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.6ql3w5pvsp6bp0a5q6p3ytjao.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.7hux34vz5g352tft4gj8l0q6q.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9hydj96220h8fwdu88aqmothz.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.auszuepxi1ewuizdno9bqrqjt.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.bnt33e19w1wlwdyp6plf9r199.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.d32eqbt4giva2ort6icyg6ns1.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.dzgpqsfv08zvcsfsjn8yv1q08.0z3sama.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657",
          "kind": "object",
          "path": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build_script_build-d095558f6ea7e657.9leq919eusuh6b0lxql90pbao.0z3sama.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-35966-1783992729662144795.map",
      "pid": 35966,
      "ppid": 35935,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-35966-1783992729662144795.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
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
      "parsed_event_count": 570,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 571,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "       37356  37351    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.185   collect2         37357  37356    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.187   ld.lld           37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n5.189   rust-lld         37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.222   cc               37380  37325    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.223   cc               37381  37327    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.223   cc               37382  37380    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.226   cc               37383  37381    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.227   collect2         37385  37382    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.228   collect2         37386  37383    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.230   ld.lld           37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n5.230   ld.lld           37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n5.232   rust-lld         37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.233   rust-lld         37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.245   build-script-bu  37393  37290    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n5.256   cc               37423  37321    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.258   cc               37424  37423    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.262   collect2         37425  37424    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.264   ld.lld           37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n5.267   rust-lld         37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.280   build-script-bu  37444  37290    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n5.283   build-script-bu  37446  37290    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n5.298   cargo            37447  36863    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n5.309   build-script-bu  37449  37290    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n5.313   rustc            37450  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n5.315   rustc            37452  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.341   rustc            37465  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.341   rustc            37464  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.342   rustc            37467  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=cbc0344642a3fe61 ...\n5.342   rustc            37466  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.373   cc               37488  37467    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.374   cc               37493  37488    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n5.378   collect2         37494  37493    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.379   ld.lld           37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n5.381   rust-lld         37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.415   cc               37518  37464    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.416   cc               37519  37466    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.417   cc               37521  37519    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.417   cc               37520  37518    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n5.420   collect2         37525  37521    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.423   ld.lld           37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n5.423   collect2         37527  37520    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.426   rustc            37526  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.427   ld.lld           37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n5.428   rust-lld         37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.429   rust-lld         37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.435   build-script-bu  37531  37447    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n5.447   cc               37568  37465    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.449   cc               37570  37568    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n5.453   collect2         37571  37570    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n5.456   ld.lld           37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n5.458   rust-lld         37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n5.483   build-script-bu  37590  37447    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n5.487   build-script-bu  37592  37447    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n5.499   build-script-bu  37594  37447    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n5.505   rustc            37596  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.567   rustc            37606  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.567   rustc            37607  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.653   rustc            37621  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=2bb0f49e2ccb2b73 ...\n5.689   rustc            37628  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.714   rustc            37636  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.774   rustc            37646  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c73793a7c0eb3dd6 ...\n5.838   rustc            37653  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.916   rustc            37661  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c16cb3cec9db833d ...\n8.451   sh               38036  2147557   0 /bin/sh -c which ps\n8.452   which            38036  2147557   0 /usr/bin/which ps\n8.455   sh               38037  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.457   ps               38037  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n8.489   sh               38038  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n8.490   cpuUsage.sh      38038  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n8.492   sed              38039  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.495   cat              38040  38038    0 /usr/bin/cat /proc/2240539/stat\n8.497   cat              38041  38038    0 /usr/bin/cat /proc/4193716/stat\n8.498   sleep            38042  38038    0 /usr/bin/sleep 1\n8.980   runc             38043  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process926607668 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.987   exe              38050  38043    0 /proc/self/exe init\n9.013   etcdctl          38053  38043    0 /usr/local/bin/etcdctl endpoint health\n9.036   16               38070  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n9.039   16               38071  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n9.197   drkonqi-coredum  38071  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 887-38069-0\n9.200   systemd-coredum  38070  1        0 /usr/lib/systemd/systemd-coredump\n9.501   sed              38082  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n9.504   cat              38083  38038    0 /usr/bin/cat /proc/2240539/stat\n9.506   cat              38085  38038    0 /usr/bin/cat /proc/4193716/stat\n9.703   9                38087  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n9.709   abrt-server      38088  1118     0 /usr/bin/abrt-server -s\n9.722   drkonqi-coredum  38087  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n9.738   abrt-handle-eve  38089  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312\n9.755   sh               38092  38089    0 /bin/sh -c abrt-action-save-package-data\\n\n9.757   abrt-action-sav  38092  38089    0 /usr/bin/abrt-action-save-package-data\n9.773   9                38095  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n9.777   plasma_waitforn  38095  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n9.821   sh               38097  38089    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n9.823   cut              38099  38097    0 /usr/bin/cut -d: -f1\n9.823   cat              38100  38098    0 /usr/bin/cat uid\n9.824   getent           38098  38097    0 /usr/bin/getent passwd 1000\n9.826   lscpu            38101  38097    0 /usr/bin/lscpu\n9.843   sh               38102  38089    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n9.845   runlevel         38103  38102    0 /usr/bin/runlevel\n9.857   sh               38104  38089    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n9.859   grep             38105  38104    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n9.861   grep             38106  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n9.863   grep             38107  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n9.865   abrt-action-cor  38108  38104    0 /usr/libexec/abrt-action-coredump -x\n9.932   abrt-action-gen  38109  38104    0 /usr/bin/abrt-action-generate-core-backtrace\n9.990   abrt-action-ana  38110  38104    0 /usr/bin/abrt-action-analyze-vulnerability\n9.993   eu-readelf       38112  38111    0 /usr/bin/eu-readelf -n coredump\n9.993   grep             38113  38111    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n9.993   sed              38114  38111    0 /usr/bin/sed s/[^0-9]//g\n9.997   gdb              38116  38115    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n10.014  iconv            38117  38116    0 /usr/bin/iconv -l\n10.118  abrt-action-ana  38126  38104    0 /usr/bin/abrt-action-analyze-c\n10.132  eu-unstrip       38127  38126    0 /usr/bin/eu-unstrip --core=./coredump -n\n10.152  abrt-action-lis  38128  38104    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n10.217  cat              38130  38129    0 /usr/bin/cat executable\n10.218  cat              38131  38129    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312/uid\n10.220  journalctl       38132  38129    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n10.231  abrt-action-cor  38133  38104    0 /usr/libexec/abrt-action-coredump -r\n10.275  abrt-handle-eve  38134  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.288  sh               38135  38134    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n10.289  dbus-send        38135  38134    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.291  sh               38136  38134    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n10.293  abrt-action-not  38137  38136    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n10.341  sh               38138  38137    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n10.342  reporter-system  38138  38137    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n12.202  16               38141  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n12.219  frpc             38141  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.786  runc             38147  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup kill --all 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 9\n17.806  runc             38153  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup delete 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n18.006  containerd-shim  38159  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 delete\n18.009  runc             38166  38159    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d109 --log-format json delete --force 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n18.058  sh               38176  38172    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc807bb6\n18.059  ethtool          38177  38176    0 /usr/sbin/ethtool -i vethc807bb6\n18.060  sed              38178  38176    0 /usr/bin/sed -n s/^driver: //p\n18.067  systemd-sysctl   38181  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc807bb6 --prefix=/net/ipv4/neigh/vethc807bb6 --prefix=/net/ipv6/conf/vethc807bb6 --prefix=/net/ipv6/neigh/vethc807bb6\n18.266  runc             38183  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup kill --all 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 9\n18.286  runc             38189  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup delete 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n18.491  containerd-shim  38195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a delete\n18.494  runc             38202  38195    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f8 --log-format json delete --force 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n18.533  systemd-sysctl   38207  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth31a3e53 --prefix=/net/ipv4/neigh/veth31a3e53 --prefix=/net/ipv6/conf/veth31a3e53 --prefix=/net/ipv6/neigh/veth31a3e53\n18.558  runc             38209  33897    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 --log-format json --systemd-cgroup kill --all 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3 9\n18.570  rustup           38215  32637    0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.577  runc             38224  33897    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 --log-format json --systemd-cgroup delete 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3\n18.772  sh               38230  2147557   0 /bin/sh -c which ps\n18.774  which            38230  2147557   0 /usr/bin/which ps\n18.776  sh               38231  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.778  ps               38231  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.791  containerd-shim  38232  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918 delete\n18.794  runc             38238  38232    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a --log-format json delete --force 1244a459993a386172e1ef83b52b2fd76894bb4a238de4bc94a43056918df2a3\n18.810  sh               38244  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.811  cpuUsage.sh      38244  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n18.813  sed              38245  38244    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.816  cat              38246  38244    0 /usr/bin/cat /proc/2240539/stat\n18.817  cat              38247  38244    0 /usr/bin/cat /proc/4193716/stat\n18.819  sleep            38248  38244    0 /usr/bin/sleep 1\n18.833  systemd-sysctl   38249  38208    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth597109a --prefix=/net/ipv4/neigh/veth597109a --prefix=/net/ipv6/conf/veth597109a --prefix=/net/ipv6/neigh/veth597109a\n"
    },
    {
      "argv": [
        "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build",
      "pid": 36002,
      "ppid": 35203,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/6863030990727937565detect_compiler_famil"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36004,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/6863030990727937565detect_compiler_famil",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
      "pid": 36013,
      "ppid": 36004,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36014,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-E",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/12036883374344146994detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36015,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
        "-E",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/12036883374344146994detect_compiler_fami",
        "-mlittle-endian",
        "-mabi=lp64",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
      "pid": 36017,
      "ppid": 36015,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36021,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
        "-c",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36028,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check.cpp",
        "-quiet",
        "-dumpbase",
        "flag_check.cpp",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
        "-O0",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
      "pid": 36029,
      "ppid": 36028,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/flag_check",
        "/tmp/ccO1Zg0s.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 36031,
      "ppid": 36028,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-w",
        "-std=c++11",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
        "-c",
        "src/implementation.cc"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-g++",
      "pid": 36036,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
        "-quiet",
        "-imultiarch",
        "aarch64-linux-gnu",
        "-D_GNU_SOURCE",
        "src/implementation.cc",
        "-quiet",
        "-dumpbase",
        "implementation.cc",
        "-mlittle-endian",
        "-mabi=lp64",
        "-auxbase-strip",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-w",
        "-std=c++11",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1plus",
      "pid": 36037,
      "ppid": 36036,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
        "-W",
        "-EL",
        "-mabi=lp64",
        "-o",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o",
        "/tmp/ccOVdRq5.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as",
      "pid": 36042,
      "ppid": 36036,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "cqD",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/48d3f1b29a630f4c-implementation.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 36047,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/aarch64-linux-gnu-ar",
        "sD",
        "/target/aarch64-unknown-linux-gnu/debug/build/iana-time-zone-haiku-0bb91afb23c9627b/out/libtz_haiku.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 36002,
      "build_script_target_dir": "iana-time-zone-haiku-d095558f6ea7e657",
      "comm": "aarch64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/aarch64-linux-gnu-ar",
      "pid": 36048,
      "ppid": 36002,
      "root_cargo_pid": 35203,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "iana-time-zone-haiku",
      "cwd": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "event_id": "bsrun:77bb561715340897:f4c3d0f1165bf29b:091aee4132cd4cef",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
      "out_dir": "/target/debug/build/iana-time-zone-haiku-d095558f6ea7e657/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "iana-time-zone-haiku",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2#iana-time-zone-haiku@0.1.2",
        "manifest_dir": "/tmp/crate-build-aarch64-v9yhyp46/src/iana-time-zone-haiku-0.1.2",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 165,
    "crate": "iana-time-zone-haiku",
    "version": "0.1.2",
    "crate_id": "683649",
    "version_id": "797963",
    "downloads": 147692627,
    "cumulative_downloads": 38617221221,
    "cumulative_share_of_global": 0.1443808751352344,
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
