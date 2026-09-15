# `vsprintf` `2.0.0`

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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
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
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60",
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
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-655153-1783995176024512142.map",
  "pid": 655153,
  "ppid": 655126,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-655153-1783995176024512142.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a`

Owner: `vsprintf` `2.0.0`

### Source files

* `/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/src/lib.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "-c",
    "src/lib.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 655357,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/lib.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "lib.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/lib.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 655358,
  "ppid": 655357,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "root_cargo_pid": 652751,
  "build_script_root_pid": 655195,
  "build_script_related": true,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 655387,
  "ppid": 655195,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "root_cargo_pid": 652751,
  "build_script_root_pid": 655195,
  "build_script_related": true,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
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
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
      "name": "vsprintf",
      "version": "2.0.0",
      "manifest_path": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0"
    }
  ],
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
  "ppid": 652835,
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

#### Record 3

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "event_id": "used:cc:f7a275179e4f3c0d:e002a5c31829b372:b35caae74eb79e12",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
  "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
  "pid": 653431,
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

#### Record 4

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
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

#### Record 5

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
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

#### Record 6

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
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

#### Record 7

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
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

#### Record 8

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "pid": 653431,
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

#### Record 9

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
    "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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

#### Record 10

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
  "context_path": "/tmp/native-trace-649454-1783995131944/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-649454-1783995131944/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 653431,
  "ppid": 652835,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
    "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT",
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
      "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT",
      "kind": "object",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
  "map_path": "/tmp/native-trace-link-cc-653431-1783995160707391742.map",
  "pid": 653431,
  "ppid": 652835,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-653431-1783995160707391742.map"
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

#### Record 12

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 655153,
  "ppid": 655126,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:b07e27d48ae7a758:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
  "pid": 655153,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:df2917578ca0df28:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "39141958f3b49fefb8181ca588c522a85e65272fe90337f8d9936046efba7645",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:ed0d01c9aa2cf1ee:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "31d077ca07a5740efd06986fdc04a0412411fc783b904a98471156d097dc2b8c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:b07a0a9123d80d3d:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "1f4fe6b6aa374d57b3cd4246d29b0e2039a2a86d15930765a5d39e66f1f0fac0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:c6e90269123233f9:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "744ad7b7141138caf92902e5a6ecc27f3ce7a1a20df14f1f2a10e04c0514889f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:9be63bd862a25a0c:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "d71c79d6e64b92ae93868a19fab5a912cb96c61f72370add0ad4ba853cedac37",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:b6614b6bbcc359c9:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "746b5ba8048f35bfcee24dcf47de1db0124bdb87408a71085589c7817fa42389",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:8677642d25b6b948:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "0544ffaa9730e42d8dd533ac6cc828b19ceb7047b25613f83f2483f34518c55b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:3c9923912b2c9c7d:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "f9b41cb6ffe4fc2d8a4abc3238e689ea12098d27b02ca2764534c70712d7099e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:50c163cc5a8807ba:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "e9e76e8eb3c250e214f023d33e797a7183559a2181fd0bdb046b75c81fb315f2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "used:cc:6b1c483a1a06b1fb:443b5c5f9c4238ec:1a72a539ba9912ac",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
  "pid": 655153,
  "sha256": "5110c7c1e33ed1472729860bf11cce90ea47e1ed4044573a2d5309ab7cc66bf8",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
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
  "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "cargo_pkg_name": "vsprintf",
  "cargo_pkg_version": "2.0.0",
  "context_path": "/tmp/native-trace-649454-1783995131944/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-649454-1783995131944/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 655153,
  "ppid": 655126,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
    "/target/debug/build/vsprintf-8841cc95d6b7dd60",
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
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
      "kind": "object",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-655153-1783995176024512142.map",
  "pid": 655153,
  "ppid": 655126,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-655153-1783995176024512142.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 27

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

#### Record 28

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 1408,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1410,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "e lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"num-bigint-std\" --cfg feature=\"std\" ...\n36.671  cat              656465 656317   0 /usr/bin/cat /proc/2240539/stat\n36.676  cat              656467 656317   0 /usr/bin/cat /proc/4193716/stat\n36.713  rustc            656471 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n36.762  cat              656452 649576   0 /usr/bin/cat\n36.763  rustc            656475 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fnv --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n36.765  rustc            656476 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) ...\n36.768  cat              656480 649576   0 /usr/bin/cat confdefs.h -\n36.772  rm               656481 649576   0 /usr/bin/rm -f conftest.o\n36.776  cc               656483 656482   0 /tmp/native-trace-643006-1783995068237/shims/cc -c conftest.c\n36.778  cc               656484 656483   0 /usr/bin/cc -c conftest.c\n36.781  cc1              656485 656484   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o /tmp/cc3TTMDa.s ...\n36.817  as               656494 656484   0 /usr/bin/as --64 -o conftest.o /tmp/cc3TTMDa.s\n36.818  rustc            656492 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_cmp --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-cmp-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=05a39fc625b95fda ...\n36.850  rm               656500 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n36.929  cc               656516 656515   0 /tmp/native-trace-643006-1783995068237/shims/cc --version\n36.931  cc               656520 656516   0 /usr/bin/cc --version -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656516-1783995186152469002.map\n36.933  head             656517 656515   0 /usr/bin/head -1\n36.940  rustc            656521 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"dfa\" --cfg feature=\"dfa-build\" ...\n36.948  cat              656522 649576   0 /usr/bin/cat confdefs.h -\n36.951  rm               656523 649576   0 /usr/bin/rm -f conftest.o\n36.954  cc               656525 656524   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n36.955  cc               656526 656525   0 /usr/bin/cc -c -fPIC conftest.c\n36.957  cc1              656527 656526   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.020  rustc            656540 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.072  as               656547 656526   0 /usr/bin/as --64 -o conftest.o /tmp/ccllYV0E.s\n37.077  rm               656549 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n37.103  rustc            656541 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_cmp --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-cmp-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=9e283e1357af4be1 ...\n37.148  as               656563 648967   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-ExpressionAnalyzer.o /tmp/cc2i2Pa2.s\n37.157  rustc            656560 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iana_time_zone --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iana-time-zone-0.1.61/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallback\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"fallback\")) ...\n37.163  cat              656551 649576   0 /usr/bin/cat confdefs.h -\n37.167  git              656564 2235138   0 /usr/bin/git worktree list --porcelain\n37.171  rm               656565 649576   0 /usr/bin/rm -f conftest.o\n37.178  cc               656567 656566   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n37.181  cc               656568 656567   0 /usr/bin/cc -c -fPIC conftest.c\n37.196  cc1              656569 656568   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.213  as               656574 656568   0 /usr/bin/as --64 -o conftest.o /tmp/ccRRPYom.s\n37.221  git              656573 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n37.223  rm               656575 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n37.237  cat              656576 649576   0 /usr/bin/cat confdefs.h -\n37.242  rm               656577 649576   0 /usr/bin/rm -f conftest.o\n37.248  cc               656579 656578   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n37.250  cc               656582 656579   0 /usr/bin/cc -c -fPIC conftest.c\n37.253  cc1              656584 656582   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.378  rustc            656558 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fnv --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.421  rustc            656593 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name better_any --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/better_any-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"any\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n37.462  rustc            656599 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uuid --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-0.8.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.488  rustc            656607 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unsafe_libyaml --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unsafe-libyaml-0.2.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7b104b2d700f5b41 ...\n37.515  as               656612 651971   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n37.614  runc             656615 648048   0 \n37.657  runc             656625 648048   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb3 --log-format json --systemd-cgroup delete 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274\n37.765  rustc            656640 656637   0 \n37.765  rustc            656640 656637   0 \n37.765  cross            656637 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n37.788  rustc            656655 656637   0 /home/xmoe/.cargo/bin/rustc -vV\n37.797  rustc            656655 656637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n37.854  cargo            656666 656637   0 \n37.866  cargo            656666 656637   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n37.882  rustc            656675 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n37.941  git              656679 2235138   0 /usr/bin/git status -z -uall\n37.961  rustc            656683 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n37.965  cc               656680 655458   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcpVjjB8/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpVjjB8/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustcpVjjB8/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n37.969  cc               656684 656680   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcpVjjB8/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpVjjB8/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustcpVjjB8/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n37.998  as               656690 656582   0 /usr/bin/as --64 -o conftest.o /tmp/ccWY59ux.s\n38.003  collect2         656691 656684   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpVjjB8/raw-dylibs ...\n38.011  rm               656692 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n38.018  cat              656693 649576   0 /usr/bin/cat confdefs.h -\n38.021  rm               656694 649576   0 /usr/bin/rm -f conftest.o\n38.027  cc               656697 656696   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n38.027  cc               656698 656697   0 \n38.033  powerpc64le-lin  656695 629465   0 \n38.034  rustc            656700 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n38.034  cc1              656699 656698   0 \n38.042  cc1plus          656701 656695   0 \n38.042  rustc            656689 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --cfg feature=\"unicode-bool\" --check-cfg cfg(docsrs,test) ...\n38.054  ld.lld           656705 656691   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpVjjB8/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n38.055  git              656682 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n38.119  rust-lld         656705 656691   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n38.183  riscv64-linux-g  656710 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n38.187  cc1plus          656711 656710   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n38.200  as               656712 656698   0 /usr/bin/as --64 -o conftest.o /tmp/ccCDsQxY.s\n38.212  cat              656713 649576   0 /usr/bin/cat confdefs.h -\n38.218  rm               656714 649576   0 /usr/bin/rm -f conftest.o\n38.220  rustc            656716 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.223  cc               656718 656717   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n38.256  rustc            656723 656637   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n38.263  rustc            656723 656637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n38.307  docker           656742 656637   0 /usr/bin/docker --help\n38.317  docker           656761 656637   0 \n38.343  cc               656719 656718   0 /usr/bin/cc -c -fPIC conftest.c\n38.357  cc1              656770 656719   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n38.373  runc             656771 1599     0 /usr/bin/runc --version\n38.384  containerd-shim  656778 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb3 delete\n38.384  docker-init      656777 1599     0 /usr/bin/docker-init --version\n38.393  runc             656786 656778   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb34427 --log-format json delete --force 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274\n38.398  docker           656793 656637   0 /usr/bin/docker info -f {{.SecurityOptions}}\n38.991  sh               656822 656816   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth1782a9e\n38.991  runc             656815 1599     0 /usr/bin/runc --version\n39.100  ethtool          656838 656822   0 /usr/sbin/ethtool -i veth1782a9e\n39.106  sed              656839 656822   0 /usr/bin/sed -n s/^driver: //p\n39.113  rustc            656836 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_rational --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-rational-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"num-bigint-std\" --cfg feature=\"std\" ...\n39.115  grep             656826 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n39.121  cat              656844 649576   0 /usr/bin/cat conftest.er1\n39.127  mv               656847 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n39.127  systemd-sysctl   656848 656816   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1782a9e --prefix=/net/ipv4/neigh/veth1782a9e --prefix=/net/ipv6/conf/veth1782a9e --prefix=/net/ipv6/neigh/veth1782a9e\n39.132  sed              656850 649576   0 /usr/bin/sed s/^/| / conftest.c\n39.141  rm               656851 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n39.142  rm               656852 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n39.147  cat              656854 649576   0 /usr/bin/cat confdefs.h -\n39.196  rm               656857 649576   0 /usr/bin/rm -f conftest.o conftest\n39.200  cc               656859 656858   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n39.204  cc               656860 656859   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656859-1783995188422756540.map\n39.206  cc1              656861 656860   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n39.210  docker-init      656862 1599     0 /usr/bin/docker-init --version\n39.265  rustc            656866 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a82bd1455e9a7070 ...\n39.353  rustc            656870 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iso8601 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iso8601-0.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n39.365  rustc            656872 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iana_time_zone --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iana-time-zone-0.1.61/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallback\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"fallback\")) ...\n39.437  rustc            656882 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=82c496c8c471e189 ...\n39.455  sh               656890 2147557   0 /bin/sh -c which ps\n39.456  which            656890 2147557   0 /usr/bin/which ps\n39.461  sh               656891 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.462  ps               656891 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.519  as               656895 630023   0 \n39.523  as               656894 656860   0 /usr/bin/as --64 -o /tmp/ccZEMEfe.o /tmp/ccTcpy1g.s\n39.545  rustc            656898 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=82805f582d26809a ...\n39.548  collect2         656896 656860   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.551  ld               656899 656896   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.554  ld               656900 656899   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.604  cat              656906 649576   0 /usr/bin/cat conftest.err\n39.606  grep             656907 649576   0 \n39.610  cat              656908 649576   0 /usr/bin/cat conftest.er1\n39.712  mv               656909 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n39.724  rm               656920 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n39.726  rm               656922 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n39.735  cat              656924 649576   0 /usr/bin/cat\n39.744  rustc            656925 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba0dd09a64170cdc ...\n39.744  cat              656926 649576   0 /usr/bin/cat confdefs.h -\n39.750  rm               656928 649576   0 /usr/bin/rm -f conftest.o conftest\n39.754  cc               656930 656929   0 \n39.755  cc               656931 656930   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656930-1783995188976224920.map\n39.758  cc1              656932 656931   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n39.764  rustc            656919 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n39.794  rustc            656936 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytecount --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytecount-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"runtime-dispatch-simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"generic-simd\", \"html_report\", \"runtime-dispatch-simd\")) ...\n39.820  cc               656942 655992   0 /tmp/native-trace-648370-1783995117170/shims/cc -Wl,--version-script=/target/debug/deps/rustccIGitl/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccIGitl/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustccIGitl/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n39.836  cc               656947 656942   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustccIGitl/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccIGitl/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustccIGitl/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n39.841  collect2         656949 656947   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustccIGitl/raw-dylibs ...\n39.849  ld.lld           656950 656949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustccIGitl/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n39.854  rust-lld         656950 656949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n39.864  rustc            656945 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uriparse --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uriparse-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\")) ...\n39.874  rustc            656948 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name base64 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.22.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n39.880  rustup           656951 656637   0 /home/xmoe/.cargo/bin/rustup toolchain list\n39.890  rustup           656961 656637   0 \n39.931  sh               656990 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n39.934  cpuUsage.sh      656990 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n39.938  sed              656991 656990   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n40.009  rustc            656994 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typed_arena --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typed-arena-2.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n40.029  cat              656997 656990   0 /usr/bin/cat /proc/2240539/stat\n40.067  cat              656998 656990   0 /usr/bin/cat /proc/4193716/stat\n40.150  sleep            657002 656990   0 /usr/bin/sleep 1\n40.184  as               657008 656931   0 /usr/bin/as --64 -o /tmp/cctwgVZW.o /tmp/ccnwNYhA.s\n40.211  rustup           657018 656637   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n40.220  rustc            657017 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) ...\n40.346  collect2         657043 656931   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.349  ld               657044 657043   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.351  ld               657045 657044   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.372  uname            657046 656637   0 /usr/bin/uname -r\n40.401  docker           657047 656637   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n40.417  rustc            657056 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n40.430  rustc            657059 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=19b1542edaa8a9a2 ...\n40.609  rustc            657060 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=bb219ed601eddc29 ...\n40.632  cat              657063 649576   0 /usr/bin/cat conftest.err\n40.634  grep             657069 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n40.708  cat              657070 649576   0 /usr/bin/cat conftest.er1\n40.837  rustc            657079 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uriparse --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uriparse-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\")) ...\n40.842  rustc            657081 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n40.974  mv               657098 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n41.279  sed              657099 649576   0 /usr/bin/sed s/^/| / conftest.c\n41.460  rustc            657104 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n41.460  sed              657112 656990   0 \n41.460  rm               657114 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n41.719  rustc            657120 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n41.748  rm               657121 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n41.790  cat              657125 656990   0 /usr/bin/cat /proc/2240539/stat\n41.793  cat              657127 656990   0 /usr/bin/cat /proc/4193716/stat\n41.851  rustc            657134 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n41.864  rustc            657136 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=cf55ba38dc1408e7 ...\n41.904  sed              657139 657138   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n41.979  sed              657149 657148   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.142  cat              657145 649576   0 /usr/bin/cat\n42.212  sed              657160 657159   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n42.249  systemd-sysctl   657166 656864   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1411d6c --prefix=/net/ipv4/neigh/veth1411d6c --prefix=/net/ipv6/conf/veth1411d6c --prefix=/net/ipv6/neigh/veth1411d6c\n42.324  sed              657172 657170   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.328  cat              657167 649576   0 /usr/bin/cat\n42.334  systemd-sysctl   657173 656816   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethff0b42f --prefix=/net/ipv4/neigh/vethff0b42f --prefix=/net/ipv6/conf/vethff0b42f --prefix=/net/ipv6/neigh/vethff0b42f\n42.367  sed              657181 657180   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n42.376  sed              657186 657185   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.446  cat              657182 649576   0 /usr/bin/cat\n42.451  cat              657192 649576   0 /usr/bin/cat confdefs.h -\n42.454  rm               657193 649576   0 /usr/bin/rm -f conftest.o conftest\n42.457  cc               657195 657194   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n42.543  cc               657207 657195   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-657195-1783995191750008765.map\n42.573  cc1              657211 657207   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n42.751  as               657233 657207   0 /usr/bin/as --64 -o /tmp/ccPjuPpI.o /tmp/ccjh35Jk.s\n43.127  collect2         657243 657207   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.195  rustc            657250 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99e7ec22f0d5ea4b ...\n43.297  ld               657252 657243   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.298  ld               657253 657252   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.340  containerd-shim  657256 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 start\n43.344  rustc            657255 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99df842a04eb3802 ...\n43.515  containerd-shim  657262 1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 -address /var/run/docker/containerd/containerd.sock\n43.530  runc             657278 657262   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6\n43.552  exe              657290 657278   0 /proc/self/exe init\n43.555  rustc            657285 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n43.877  rustc            657318 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n43.904  rustc            657320 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n43.940  exe              657328 657278   0 /proc/1599/exe -exec-root=/var/run/docker 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 d7da31e8f8e1\n44.009  rustc            657336 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fraction --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fraction-0.15.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lazy_static\" --cfg feature=\"with-bigint\" --check-cfg cfg(docsrs,test) ...\n44.113  git              657346 2235138   0 /usr/bin/git config --get commit.template\n44.137  git              657347 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n44.147  rm               657348 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n44.152  rm               657350 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n44.158  cat              657351 649576   0 /usr/bin/cat\n44.162  cat              657352 649576   0 /usr/bin/cat confdefs.h -\n44.166  cc               657354 657353   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n44.167  cc               657355 657354   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-657354-1783995193388105927.map\n44.170  cc1              657356 657355   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n44.268  git              657366 2235138   0 /usr/bin/git status -z -uall\n44.290  git              657368 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n44.308  rustc            657364 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n44.319  rustc            657369 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=12db262aa6b622b6 ...\n44.327  rustc            657362 649548   0 \n44.478  rustc            657373 650847   0 \n44.478  16               657378 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n44.526  sh               657379 2147557   0 /bin/sh -c which ps\n44.526  which            657379 2147557   0 /usr/bin/which ps\n44.528  sh               657387 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n44.533  ps               657387 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n44.569  rustc            657393 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n44.572  exe              657395 1599     0 /proc/self/exe /var/run/docker/netns/220aaefc07ee all false\n44.608  frpc             657378 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n44.755  as               657407 657355   0 /usr/bin/as --64 -o /tmp/ccD4uzNA.o /tmp/ccl179gn.s\n44.781  collect2         657412 657355   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.846  ld               657422 657412   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.849  ld               657423 657422   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.955  rustc            657430 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fraction --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fraction-0.15.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lazy_static\" --cfg feature=\"with-bigint\" --check-cfg cfg(docsrs,test) ...\n45.094  runc             657439 657262   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --log-format json --systemd-cgroup start 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6\n45.103  sh               657301 657262   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n45.106  cargo            657445 657301   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n45.128  cargo-native-tr  657445 657301   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n45.148  cargo            657448 657445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n45.218  rustc            657450 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4c59b5f118cfa852 ...\n45.291  sh               657458 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n45.293  cpuUsage.sh      657458 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n45.295  sed              657459 657458   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n45.299  cat              657460 657458   0 /usr/bin/cat /proc/2240539/stat\n45.316  cross            657461 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n45.317  rustc            657464 657461   0 /home/xmoe/.cargo/bin/rustc --print target-list\n45.503  conftest         657465 657457   0 ./conftest\n45.504  rm               657480 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n45.529  rustc            657470 657448   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n45.536  cat              657479 657458   0 /usr/bin/cat /proc/4193716/stat\n45.537  sleep            657487 657458   0 /usr/bin/sleep 1\n45.542  rm               657488 649576   0 /usr/bin/rm -f core *.core core.conftest.* gmon.out bb.out conftest conftest.o conftest.beam conftest.c\n45.544  rm               657489 649576   0 /usr/bin/rm -f conftest.mmap conftest.txt\n45.546  sed              657493 657492   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n45.549  cat              657494 649576   0 /usr/bin/cat confdefs.h -\n45.550  rm               657495 649576   0 /usr/bin/rm -f conftest.o conftest\n45.622  rustc            657464 657461   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n45.657  cc               657498 657497   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n45.886  rustc            657507 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=db300de5ecb26797 ...\n"
}
```

#### Record 29

```json
{
  "argv": [
    "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 653572,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
  "pid": 653572,
  "ppid": 652751,
  "root_cargo_pid": 652751,
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

#### Record 30

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 653572,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 653579,
  "ppid": 653572,
  "root_cargo_pid": 652751,
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

#### Record 31

```json
{
  "argv": [
    "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build",
  "pid": 655195,
  "ppid": 652751,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out"
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/7149816165832455671detect_compiler_family.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 655200,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/7149816165832455671detect_compiler_family.c",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 655205,
  "ppid": 655200,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 34

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 655323,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-Wall",
    "-Wextra",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "-c",
    "src/lib.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
  "pid": 655357,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/lib.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "lib.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "pid": 655358,
  "ppid": 655357,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "/tmp/ccWbRBXe.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 655386,
  "ppid": 655357,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 655387,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "sD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 655195,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 655389,
  "ppid": 655195,
  "root_cargo_pid": 652751,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 40

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

#### Record 41

```json
{
  "crate": "vsprintf",
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "event_id": "bsrun:856b55980d4c0017:e82f1a6d95b7b914:48a63d51fcaf27de",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
  "success": true,
  "target": null,
  "version": "2.0.0",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 42

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 653572,
  "build_script_target_dir": "libc-8a22300c8f78b6db",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 653579,
  "ppid": 653572,
  "root_cargo_pid": 652751,
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
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "src/lib.c",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "lib.c",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
    "-g",
    "-gdwarf-4",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "src/lib.c",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 655358,
  "ppid": 655357,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "root_cargo_pid": 652751,
  "build_script_root_pid": 655195,
  "build_script_related": true,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 44

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cqD",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 655387,
  "ppid": 655195,
  "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "root_cargo_pid": 652751,
  "build_script_root_pid": 655195,
  "build_script_related": true,
  "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
  "_owner": {
    "crate": "vsprintf",
    "version": "2.0.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
  "_build_script_out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:13:17.352002+00:00",
  "crate": "vsprintf",
  "version": "2.0.0",
  "architecture": "ppc64le",
  "duration_seconds": 74.24812347302213,
  "trace_record_count": 41,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
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
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "manifest_path": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 28,
    "unattributed_event_count": 13,
    "owners": [
      {
        "crate": "vsprintf",
        "version": "2.0.0",
        "event_count": 17,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 11,
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
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
          "name": "vsprintf",
          "version": "2.0.0",
          "manifest_path": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0"
        }
      ],
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
      "ppid": 652835,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "event_id": "used:cc:f7a275179e4f3c0d:e002a5c31829b372:b35caae74eb79e12",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db",
      "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "pid": 653431,
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o",
        "/target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
      "context_path": "/tmp/native-trace-649454-1783995131944/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-649454-1783995131944/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 653431,
      "ppid": 652835,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/raw-dylibs",
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
        "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT",
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
          "directory": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT",
          "kind": "object",
          "path": "/target/debug/build/libc-8a22300c8f78b6db/rustcrX18pT/symbols.o",
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
      "map_path": "/tmp/native-trace-link-cc-653431-1783995160707391742.map",
      "pid": 653431,
      "ppid": 652835,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-653431-1783995160707391742.map"
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
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 655153,
      "ppid": 655126,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:b07e27d48ae7a758:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
      "pid": 655153,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:df2917578ca0df28:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "39141958f3b49fefb8181ca588c522a85e65272fe90337f8d9936046efba7645",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:ed0d01c9aa2cf1ee:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "31d077ca07a5740efd06986fdc04a0412411fc783b904a98471156d097dc2b8c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:b07a0a9123d80d3d:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "1f4fe6b6aa374d57b3cd4246d29b0e2039a2a86d15930765a5d39e66f1f0fac0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:c6e90269123233f9:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "744ad7b7141138caf92902e5a6ecc27f3ce7a1a20df14f1f2a10e04c0514889f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:9be63bd862a25a0c:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "d71c79d6e64b92ae93868a19fab5a912cb96c61f72370add0ad4ba853cedac37",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:b6614b6bbcc359c9:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "746b5ba8048f35bfcee24dcf47de1db0124bdb87408a71085589c7817fa42389",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:8677642d25b6b948:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "0544ffaa9730e42d8dd533ac6cc828b19ceb7047b25613f83f2483f34518c55b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:3c9923912b2c9c7d:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "f9b41cb6ffe4fc2d8a4abc3238e689ea12098d27b02ca2764534c70712d7099e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:50c163cc5a8807ba:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "e9e76e8eb3c250e214f023d33e797a7183559a2181fd0bdb046b75c81fb315f2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "used:cc:6b1c483a1a06b1fb:443b5c5f9c4238ec:1a72a539ba9912ac",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
      "pid": 655153,
      "sha256": "5110c7c1e33ed1472729860bf11cce90ea47e1ed4044573a2d5309ab7cc66bf8",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
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
      "output": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "cargo_pkg_name": "vsprintf",
      "cargo_pkg_version": "2.0.0",
      "context_path": "/tmp/native-trace-649454-1783995131944/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-649454-1783995131944/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 655153,
      "ppid": 655126,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
        "/target/debug/build/vsprintf-8841cc95d6b7dd60",
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
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/rustczrcnoJ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.05zyihhq39t8ucgcvbtzwb8t4.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.0r2lek9vd6l6oan10zfb5zri4.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.1ewqhetynnij2fgo1i058utdg.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.38oht8fglz0wu702u5ydwit3g.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.4b9xfhi419c8yx1dac33wyk0m.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.5s6tb01j9zmsw8k3p201d77to.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.6rvqt8rbhtzi5l46wm5j6oig5.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.8s7khwb47bar6efgvqwaolpug.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.e8z3ry3xofggp0txz37abxd1y.0vivm1h.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/vsprintf-8841cc95d6b7dd60",
          "kind": "object",
          "path": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build_script_build-8841cc95d6b7dd60.267r6s08h2b92crmv7zp8xygm.0vivm1h.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-655153-1783995176024512142.map",
      "pid": 655153,
      "ppid": 655126,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-655153-1783995176024512142.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
      "parsed_event_count": 1408,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1410,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "e lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"num-bigint-std\" --cfg feature=\"std\" ...\n36.671  cat              656465 656317   0 /usr/bin/cat /proc/2240539/stat\n36.676  cat              656467 656317   0 /usr/bin/cat /proc/4193716/stat\n36.713  rustc            656471 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n36.762  cat              656452 649576   0 /usr/bin/cat\n36.763  rustc            656475 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fnv --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n36.765  rustc            656476 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) ...\n36.768  cat              656480 649576   0 /usr/bin/cat confdefs.h -\n36.772  rm               656481 649576   0 /usr/bin/rm -f conftest.o\n36.776  cc               656483 656482   0 /tmp/native-trace-643006-1783995068237/shims/cc -c conftest.c\n36.778  cc               656484 656483   0 /usr/bin/cc -c conftest.c\n36.781  cc1              656485 656484   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o /tmp/cc3TTMDa.s ...\n36.817  as               656494 656484   0 /usr/bin/as --64 -o conftest.o /tmp/cc3TTMDa.s\n36.818  rustc            656492 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_cmp --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-cmp-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=05a39fc625b95fda ...\n36.850  rm               656500 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n36.929  cc               656516 656515   0 /tmp/native-trace-643006-1783995068237/shims/cc --version\n36.931  cc               656520 656516   0 /usr/bin/cc --version -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656516-1783995186152469002.map\n36.933  head             656517 656515   0 /usr/bin/head -1\n36.940  rustc            656521 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"dfa\" --cfg feature=\"dfa-build\" ...\n36.948  cat              656522 649576   0 /usr/bin/cat confdefs.h -\n36.951  rm               656523 649576   0 /usr/bin/rm -f conftest.o\n36.954  cc               656525 656524   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n36.955  cc               656526 656525   0 /usr/bin/cc -c -fPIC conftest.c\n36.957  cc1              656527 656526   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.020  rustc            656540 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.072  as               656547 656526   0 /usr/bin/as --64 -o conftest.o /tmp/ccllYV0E.s\n37.077  rm               656549 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n37.103  rustc            656541 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_cmp --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-cmp-0.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"i128\")) -C metadata=9e283e1357af4be1 ...\n37.148  as               656563 648967   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as -W -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out -a64 -mpower8 -many -mlittle -o /target/powerpc64le-unknown-linux-gnu/debug/build/wasm-opt-sys-a587b94442619b18/out/f7deeeb1a9f9c241-ExpressionAnalyzer.o /tmp/cc2i2Pa2.s\n37.157  rustc            656560 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iana_time_zone --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iana-time-zone-0.1.61/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallback\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"fallback\")) ...\n37.163  cat              656551 649576   0 /usr/bin/cat confdefs.h -\n37.167  git              656564 2235138   0 /usr/bin/git worktree list --porcelain\n37.171  rm               656565 649576   0 /usr/bin/rm -f conftest.o\n37.178  cc               656567 656566   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n37.181  cc               656568 656567   0 /usr/bin/cc -c -fPIC conftest.c\n37.196  cc1              656569 656568   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.213  as               656574 656568   0 /usr/bin/as --64 -o conftest.o /tmp/ccRRPYom.s\n37.221  git              656573 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n37.223  rm               656575 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n37.237  cat              656576 649576   0 /usr/bin/cat confdefs.h -\n37.242  rm               656577 649576   0 /usr/bin/rm -f conftest.o\n37.248  cc               656579 656578   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n37.250  cc               656582 656579   0 /usr/bin/cc -c -fPIC conftest.c\n37.253  cc1              656584 656582   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n37.378  rustc            656558 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fnv --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fnv-1.0.7/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.421  rustc            656593 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name better_any --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/better_any-0.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"any\" --cfg feature=\"default\" --check-cfg cfg(docsrs,test) ...\n37.462  rustc            656599 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uuid --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-0.8.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n37.488  rustc            656607 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unsafe_libyaml --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unsafe-libyaml-0.2.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=7b104b2d700f5b41 ...\n37.515  as               656612 651971   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -W -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o ...\n37.614  runc             656615 648048   0 \n37.657  runc             656625 648048   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb3 --log-format json --systemd-cgroup delete 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274\n37.765  rustc            656640 656637   0 \n37.765  rustc            656640 656637   0 \n37.765  cross            656637 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n37.788  rustc            656655 656637   0 /home/xmoe/.cargo/bin/rustc -vV\n37.797  rustc            656655 656637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n37.854  cargo            656666 656637   0 \n37.866  cargo            656666 656637   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n37.882  rustc            656675 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n37.941  git              656679 2235138   0 /usr/bin/git status -z -uall\n37.961  rustc            656683 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n37.965  cc               656680 655458   0 /tmp/native-trace-647230-1783995108983/shims/cc -Wl,--version-script=/target/debug/deps/rustcpVjjB8/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpVjjB8/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustcpVjjB8/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n37.969  cc               656684 656680   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcpVjjB8/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcpVjjB8/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustcpVjjB8/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n37.998  as               656690 656582   0 /usr/bin/as --64 -o conftest.o /tmp/ccWY59ux.s\n38.003  collect2         656691 656684   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpVjjB8/raw-dylibs ...\n38.011  rm               656692 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n38.018  cat              656693 649576   0 /usr/bin/cat confdefs.h -\n38.021  rm               656694 649576   0 /usr/bin/rm -f conftest.o\n38.027  cc               656697 656696   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n38.027  cc               656698 656697   0 \n38.033  powerpc64le-lin  656695 629465   0 \n38.034  rustc            656700 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n38.034  cc1              656699 656698   0 \n38.042  cc1plus          656701 656695   0 \n38.042  rustc            656689 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.11.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --cfg feature=\"unicode-bool\" --check-cfg cfg(docsrs,test) ...\n38.054  ld.lld           656705 656691   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcpVjjB8/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n38.055  git              656682 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n38.119  rust-lld         656705 656691   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd7iizy.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n38.183  riscv64-linux-g  656710 629151   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out ...\n38.187  cc1plus          656711 656710   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out/cxxbridge/crate -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src -I /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-opt-sys-0.116.0/binaryen/src/tools -I /target/riscv64gc-unknown-linux-gnu/debug/build/wasm-opt-sys-51495d9e8205139b/out -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE -D THROW_ON_FATAL -D ...\n38.200  as               656712 656698   0 /usr/bin/as --64 -o conftest.o /tmp/ccCDsQxY.s\n38.212  cat              656713 649576   0 /usr/bin/cat confdefs.h -\n38.218  rm               656714 649576   0 /usr/bin/rm -f conftest.o\n38.220  rustc            656716 656666   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.223  cc               656718 656717   0 /tmp/native-trace-643006-1783995068237/shims/cc -c -fPIC conftest.c\n38.256  rustc            656723 656637   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n38.263  rustc            656723 656637   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n38.307  docker           656742 656637   0 /usr/bin/docker --help\n38.317  docker           656761 656637   0 \n38.343  cc               656719 656718   0 /usr/bin/cc -c -fPIC conftest.c\n38.357  cc1              656770 656719   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n38.373  runc             656771 1599     0 /usr/bin/runc --version\n38.384  containerd-shim  656778 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb3 delete\n38.384  docker-init      656777 1599     0 /usr/bin/docker-init --version\n38.393  runc             656786 656778   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb34427 --log-format json delete --force 39c044daa457ee3b3507d3138ca6af32b124791d8905397e8fbb0f0bfb344274\n38.398  docker           656793 656637   0 /usr/bin/docker info -f {{.SecurityOptions}}\n38.991  sh               656822 656816   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth1782a9e\n38.991  runc             656815 1599     0 /usr/bin/runc --version\n39.100  ethtool          656838 656822   0 /usr/sbin/ethtool -i veth1782a9e\n39.106  sed              656839 656822   0 /usr/bin/sed -n s/^driver: //p\n39.113  rustc            656836 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_rational --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-rational-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"num-bigint-std\" --cfg feature=\"std\" ...\n39.115  grep             656826 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n39.121  cat              656844 649576   0 /usr/bin/cat conftest.er1\n39.127  mv               656847 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n39.127  systemd-sysctl   656848 656816   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1782a9e --prefix=/net/ipv4/neigh/veth1782a9e --prefix=/net/ipv6/conf/veth1782a9e --prefix=/net/ipv6/neigh/veth1782a9e\n39.132  sed              656850 649576   0 /usr/bin/sed s/^/| / conftest.c\n39.141  rm               656851 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n39.142  rm               656852 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest.c\n39.147  cat              656854 649576   0 /usr/bin/cat confdefs.h -\n39.196  rm               656857 649576   0 /usr/bin/rm -f conftest.o conftest\n39.200  cc               656859 656858   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n39.204  cc               656860 656859   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656859-1783995188422756540.map\n39.206  cc1              656861 656860   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n39.210  docker-init      656862 1599     0 /usr/bin/docker-init --version\n39.265  rustc            656866 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=a82bd1455e9a7070 ...\n39.353  rustc            656870 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iso8601 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iso8601-0.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n39.365  rustc            656872 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name iana_time_zone --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/iana-time-zone-0.1.61/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"fallback\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"fallback\")) ...\n39.437  rustc            656882 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=82c496c8c471e189 ...\n39.455  sh               656890 2147557   0 /bin/sh -c which ps\n39.456  which            656890 2147557   0 /usr/bin/which ps\n39.461  sh               656891 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.462  ps               656891 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.519  as               656895 630023   0 \n39.523  as               656894 656860   0 /usr/bin/as --64 -o /tmp/ccZEMEfe.o /tmp/ccTcpy1g.s\n39.545  rustc            656898 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=82805f582d26809a ...\n39.548  collect2         656896 656860   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.551  ld               656899 656896   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.554  ld               656900 656899   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqTu7KI.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n39.604  cat              656906 649576   0 /usr/bin/cat conftest.err\n39.606  grep             656907 649576   0 \n39.610  cat              656908 649576   0 /usr/bin/cat conftest.er1\n39.712  mv               656909 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n39.724  rm               656920 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n39.726  rm               656922 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n39.735  cat              656924 649576   0 /usr/bin/cat\n39.744  rustc            656925 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ba0dd09a64170cdc ...\n39.744  cat              656926 649576   0 /usr/bin/cat confdefs.h -\n39.750  rm               656928 649576   0 /usr/bin/rm -f conftest.o conftest\n39.754  cc               656930 656929   0 \n39.755  cc               656931 656930   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-656930-1783995188976224920.map\n39.758  cc1              656932 656931   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n39.764  rustc            656919 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n39.794  rustc            656936 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name bytecount --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bytecount-0.6.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"runtime-dispatch-simd\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"generic-simd\", \"html_report\", \"runtime-dispatch-simd\")) ...\n39.820  cc               656942 655992   0 /tmp/native-trace-648370-1783995117170/shims/cc -Wl,--version-script=/target/debug/deps/rustccIGitl/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccIGitl/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustccIGitl/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n39.836  cc               656947 656942   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustccIGitl/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustccIGitl/symbols.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.0.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.1.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.2.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.3.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.4.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.5.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.6.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.7.rcgu.o /target/debug/deps/rustversion-b20b80c993e0c9ce.rustversion.b66299c39a4687a4-cgu.8.rcgu.o /target/debug/deps/rustccIGitl/rmeta.o /target/debug/deps/rustversion-b20b80c993e0c9ce.4mt2jcqkpvjl0v61wl8wbe938.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- ...\n39.841  collect2         656949 656947   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustccIGitl/raw-dylibs ...\n39.849  ld.lld           656950 656949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustccIGitl/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n39.854  rust-lld         656950 656949   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cctQSInr.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/librustversion-b20b80c993e0c9ce.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n39.864  rustc            656945 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uriparse --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uriparse-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\")) ...\n39.874  rustc            656948 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name base64 --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/base64-0.22.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n39.880  rustup           656951 656637   0 /home/xmoe/.cargo/bin/rustup toolchain list\n39.890  rustup           656961 656637   0 \n39.931  sh               656990 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n39.934  cpuUsage.sh      656990 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n39.938  sed              656991 656990   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n40.009  rustc            656994 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name typed_arena --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/typed-arena-2.0.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n40.029  cat              656997 656990   0 /usr/bin/cat /proc/2240539/stat\n40.067  cat              656998 656990   0 /usr/bin/cat /proc/4193716/stat\n40.150  sleep            657002 656990   0 /usr/bin/sleep 1\n40.184  as               657008 656931   0 /usr/bin/as --64 -o /tmp/cctwgVZW.o /tmp/ccnwNYhA.s\n40.211  rustup           657018 656637   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n40.220  rustc            657017 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name either --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"use_std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\", \"use_std\")) ...\n40.346  collect2         657043 656931   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.349  ld               657044 657043   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.351  ld               657045 657044   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7yhbo4.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n40.372  uname            657046 656637   0 /usr/bin/uname -r\n40.401  docker           657047 656637   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n40.417  rustc            657056 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n40.430  rustc            657059 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=19b1542edaa8a9a2 ...\n40.609  rustc            657060 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name antlr_rust --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/antlr-rust-0.3.0-beta/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=bb219ed601eddc29 ...\n40.632  cat              657063 649576   0 /usr/bin/cat conftest.err\n40.634  grep             657069 649576   0 /usr/bin/grep -v ^ *+ conftest.err\n40.708  cat              657070 649576   0 /usr/bin/cat conftest.er1\n40.837  rustc            657079 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name uriparse --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uriparse-0.6.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"serde\")) ...\n40.842  rustc            657081 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n40.974  mv               657098 649576   0 /usr/bin/mv -f conftest.er1 conftest.err\n41.279  sed              657099 649576   0 /usr/bin/sed s/^/| / conftest.c\n41.460  rustc            657104 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name semver --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/semver-1.0.26/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n41.460  sed              657112 656990   0 \n41.460  rm               657114 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n41.719  rustc            657120 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n41.748  rm               657121 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n41.790  cat              657125 656990   0 /usr/bin/cat /proc/2240539/stat\n41.793  cat              657127 656990   0 /usr/bin/cat /proc/4193716/stat\n41.851  rustc            657134 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name chrono --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/chrono-0.4.41/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"android-tzdata\" --cfg feature=\"clock\" ...\n41.864  rustc            657136 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=cf55ba38dc1408e7 ...\n41.904  sed              657139 657138   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n41.979  sed              657149 657148   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.142  cat              657145 649576   0 /usr/bin/cat\n42.212  sed              657160 657159   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n42.249  systemd-sysctl   657166 656864   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1411d6c --prefix=/net/ipv4/neigh/veth1411d6c --prefix=/net/ipv6/conf/veth1411d6c --prefix=/net/ipv6/neigh/veth1411d6c\n42.324  sed              657172 657170   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.328  cat              657167 649576   0 /usr/bin/cat\n42.334  systemd-sysctl   657173 656816   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethff0b42f --prefix=/net/ipv4/neigh/vethff0b42f --prefix=/net/ipv6/conf/vethff0b42f --prefix=/net/ipv6/neigh/vethff0b42f\n42.367  sed              657181 657180   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n42.376  sed              657186 657185   0 /usr/bin/sed y%*abcdefghijklmnopqrstuvwxyz%PABCDEFGHIJKLMNOPQRSTUVWXYZ%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%\n42.446  cat              657182 649576   0 /usr/bin/cat\n42.451  cat              657192 649576   0 /usr/bin/cat confdefs.h -\n42.454  rm               657193 649576   0 /usr/bin/rm -f conftest.o conftest\n42.457  cc               657195 657194   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n42.543  cc               657207 657195   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-657195-1783995191750008765.map\n42.573  cc1              657211 657207   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n42.751  as               657233 657207   0 /usr/bin/as --64 -o /tmp/ccPjuPpI.o /tmp/ccjh35Jk.s\n43.127  collect2         657243 657207   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.195  rustc            657250 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name heck --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/heck-0.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99e7ec22f0d5ea4b ...\n43.297  ld               657252 657243   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.298  ld               657253 657252   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNzFf76.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n43.340  containerd-shim  657256 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 start\n43.344  rustc            657255 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99df842a04eb3802 ...\n43.515  containerd-shim  657262 1        0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 -address /var/run/docker/containerd/containerd.sock\n43.530  runc             657278 657262   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6\n43.552  exe              657290 657278   0 /proc/self/exe init\n43.555  rustc            657285 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n43.877  rustc            657318 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-0.4.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"num-bigint\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n43.904  rustc            657320 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name itertools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.14.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"use_alloc\" --cfg feature=\"use_std\" ...\n43.940  exe              657328 657278   0 /proc/1599/exe -exec-root=/var/run/docker 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6 d7da31e8f8e1\n44.009  rustc            657336 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fraction --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fraction-0.15.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lazy_static\" --cfg feature=\"with-bigint\" --check-cfg cfg(docsrs,test) ...\n44.113  git              657346 2235138   0 /usr/bin/git config --get commit.template\n44.137  git              657347 2235138   0 /usr/bin/git for-each-ref --format=%(refname)%00%(upstream:short)%00%(objectname)%00%(upstream:track)%00%(upstream:remotename)%00%(upstream:remoteref) refs/heads/master refs/remotes/master\n44.147  rm               657348 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n44.152  rm               657350 649576   0 /usr/bin/rm -f core conftest.err conftest.o conftest conftest.c\n44.158  cat              657351 649576   0 /usr/bin/cat\n44.162  cat              657352 649576   0 /usr/bin/cat confdefs.h -\n44.166  cc               657354 657353   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n44.167  cc               657355 657354   0 /usr/bin/cc -o conftest -fPIC conftest.c -Wl,--trace -Wl,-Map,/tmp/native-trace-link-cc-657354-1783995193388105927.map\n44.170  cc1              657356 657355   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -imultiarch x86_64-linux-gnu conftest.c -quiet -dumpbase conftest.c -dumpbase-ext .c -mtune=generic -march=x86-64 -fPIC -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection -fcf-protection -o ...\n44.268  git              657366 2235138   0 /usr/bin/git status -z -uall\n44.290  git              657368 2235138   0 /usr/bin/git for-each-ref --sort -committerdate --format %(refname)%00%(objectname)%00%(*objectname)\n44.308  rustc            657364 649554   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n44.319  rustc            657369 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name glob --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/glob-0.3.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=12db262aa6b622b6 ...\n44.327  rustc            657362 649548   0 \n44.478  rustc            657373 650847   0 \n44.478  16               657378 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n44.526  sh               657379 2147557   0 /bin/sh -c which ps\n44.526  which            657379 2147557   0 /usr/bin/which ps\n44.528  sh               657387 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n44.533  ps               657387 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n44.569  rustc            657393 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name strum --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/strum-0.27.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n44.572  exe              657395 1599     0 /proc/self/exe /var/run/docker/netns/220aaefc07ee all false\n44.608  frpc             657378 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n44.755  as               657407 657355   0 /usr/bin/as --64 -o /tmp/ccD4uzNA.o /tmp/ccl179gn.s\n44.781  collect2         657412 657355   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.846  ld               657422 657412   0 /tmp/native-trace-643006-1783995068237/shims/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.849  ld               657423 657422   0 /usr/bin/ld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccvxhOvT.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z ...\n44.955  rustc            657430 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fraction --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fraction-0.15.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"lazy_static\" --cfg feature=\"with-bigint\" --check-cfg cfg(docsrs,test) ...\n45.094  runc             657439 657262   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fc --log-format json --systemd-cgroup start 6501b87a587fad9d75b39629e044262ac3eb3f3e95fdd6994df11a2e3fcb63e6\n45.103  sh               657301 657262   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n45.106  cargo            657445 657301   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n45.128  cargo-native-tr  657445 657301   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n45.148  cargo            657448 657445   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n45.218  rustc            657450 649548   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=4c59b5f118cfa852 ...\n45.291  sh               657458 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n45.293  cpuUsage.sh      657458 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n45.295  sed              657459 657458   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n45.299  cat              657460 657458   0 /usr/bin/cat /proc/2240539/stat\n45.316  cross            657461 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n45.317  rustc            657464 657461   0 /home/xmoe/.cargo/bin/rustc --print target-list\n45.503  conftest         657465 657457   0 ./conftest\n45.504  rm               657480 649576   0 /usr/bin/rm -rf conftest.dSYM conftest_ipa8_conftest.oo\n45.529  rustc            657470 657448   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n45.536  cat              657479 657458   0 /usr/bin/cat /proc/4193716/stat\n45.537  sleep            657487 657458   0 /usr/bin/sleep 1\n45.542  rm               657488 649576   0 /usr/bin/rm -f core *.core core.conftest.* gmon.out bb.out conftest conftest.o conftest.beam conftest.c\n45.544  rm               657489 649576   0 /usr/bin/rm -f conftest.mmap conftest.txt\n45.546  sed              657493 657492   0 /usr/bin/sed y%*+%pp%;s%[^_abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789]%_%g\n45.549  cat              657494 649576   0 /usr/bin/cat confdefs.h -\n45.550  rm               657495 649576   0 /usr/bin/rm -f conftest.o conftest\n45.622  rustc            657464 657461   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n45.657  cc               657498 657497   0 /tmp/native-trace-643006-1783995068237/shims/cc -o conftest -fPIC conftest.c\n45.886  rustc            657507 650847   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name float_pretty_print --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/float-pretty-print-0.1.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=db300de5ecb26797 ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a22300c8f78b6db/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 653572,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a22300c8f78b6db/build-script-build",
      "pid": 653572,
      "ppid": 652751,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 653572,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 653579,
      "ppid": 653572,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build",
      "pid": 655195,
      "ppid": 652751,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/7149816165832455671detect_compiler_family.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 655200,
      "ppid": 655195,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/7149816165832455671detect_compiler_family.c",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 655205,
      "ppid": 655200,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 655323,
      "ppid": 655195,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-Wall",
        "-Wextra",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
        "-c",
        "src/lib.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-gcc",
      "pid": 655357,
      "ppid": 655195,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "src/lib.c",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "lib.c",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
        "-g",
        "-gdwarf-4",
        "-O0",
        "-Wall",
        "-Wextra",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1",
      "pid": 655358,
      "ppid": 655357,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o",
        "/tmp/ccWbRBXe.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 655386,
      "ppid": 655357,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cqD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/ea708c7824d36062-lib.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 655387,
      "ppid": 655195,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "sD",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/vsprintf-28a26ec929301317/out/libvsprintf.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 655195,
      "build_script_target_dir": "vsprintf-8841cc95d6b7dd60",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 655389,
      "ppid": 655195,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
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
    },
    {
      "crate": "vsprintf",
      "cwd": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "event_id": "bsrun:856b55980d4c0017:e82f1a6d95b7b914:48a63d51fcaf27de",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/vsprintf-8841cc95d6b7dd60/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
      "out_dir": "/target/debug/build/vsprintf-8841cc95d6b7dd60/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
      "success": true,
      "target": null,
      "version": "2.0.0",
      "_owner": {
        "crate": "vsprintf",
        "version": "2.0.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0#vsprintf@2.0.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-nj8idru8/src/vsprintf-2.0.0",
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
      "build_script_root_pid": 653572,
      "build_script_target_dir": "libc-8a22300c8f78b6db",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 653579,
      "ppid": 653572,
      "root_cargo_pid": 652751,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 2501,
    "crate": "vsprintf",
    "version": "2.0.0",
    "crate_id": "22709",
    "version_id": "257928",
    "downloads": 5004182,
    "cumulative_downloads": 104724368985,
    "cumulative_share_of_global": 0.3915402394053447,
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
