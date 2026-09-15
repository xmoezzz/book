# `async-fs` `1.6.0`

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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
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
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0",
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
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1263987-1784008649594802118.map",
  "pid": 1263987,
  "ppid": 1263965,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1263987-1784008649594802118.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-channel@2.5.0",
      "name": "async-channel",
      "version": "2.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
      "name": "async-fs",
      "version": "1.6.0",
      "manifest_path": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-lock@2.8.0",
      "name": "async-lock",
      "version": "2.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-task@4.7.1",
      "name": "async-task",
      "version": "4.7.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
      "name": "atomic-waker",
      "version": "1.1.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#blocking@1.6.2",
      "name": "blocking",
      "version": "1.6.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
      "name": "cfg-if",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.5.0",
      "name": "concurrent-queue",
      "version": "2.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
      "name": "crossbeam-utils",
      "version": "0.8.22",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@2.5.3",
      "name": "event-listener",
      "version": "2.5.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@5.4.1",
      "name": "event-listener",
      "version": "5.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener-strategy@0.5.4",
      "name": "event-listener-strategy",
      "version": "0.5.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@1.9.0",
      "name": "fastrand",
      "version": "1.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
      "name": "fastrand",
      "version": "2.4.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
      "name": "futures-core",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.32",
      "name": "futures-io",
      "version": "0.3.32",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@1.13.0",
      "name": "futures-lite",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@2.6.1",
      "name": "futures-lite",
      "version": "2.6.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.13",
      "name": "instant",
      "version": "0.1.13",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking@2.2.1",
      "name": "parking",
      "version": "2.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
      "name": "pin-project-lite",
      "version": "0.2.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#piper@0.2.5",
      "name": "piper",
      "version": "0.2.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#waker-fn@1.2.0",
      "name": "waker-fn",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0"
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
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1263914,
  "ppid": 1263813,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "crossbeam-utils",
  "cargo_pkg_version": "0.8.22",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "event_id": "used:cc:798ba4f38ec52baf:fa58978e61434f9c:9448fe032432c550",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
  "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
  "pid": 1263914,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "crossbeam-utils",
  "cargo_pkg_version": "0.8.22",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "event_id": "used:cc:798ba4f38ec52baf:21b811b731cdea94:9448fe032432c550",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
  "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
  "pid": 1263914,
  "sha256": "7d84f9518dbf41ddad736e70480ba6fc99f6db7f73f24d33baed1f6abdd61500",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "crossbeam-utils",
  "cargo_pkg_version": "0.8.22",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "event_id": "used:cc:798ba4f38ec52baf:0040a6fc5ad76d66:9448fe032432c550",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
  "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
  "pid": 1263914,
  "sha256": "2b957730a597af89266d18dbc3c53a6794d59fc06c120ea8afcfd6bcaf69bdb1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "crossbeam-utils",
  "cargo_pkg_version": "0.8.22",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "event_id": "used:cc:798ba4f38ec52baf:9e1dd1d958bb46cb:9448fe032432c550",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
  "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
  "pid": 1263914,
  "sha256": "c626d4a76490e8a47df23077d3ce0e1a8f10d449dfa06fb23e7f0431455eb08a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
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
  "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "cargo_pkg_name": "crossbeam-utils",
  "cargo_pkg_version": "0.8.22",
  "context_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1263914,
  "ppid": 1263813,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z",
    "/target/debug/build/crossbeam-utils-f32885586ba8a911",
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
      "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z",
      "kind": "object",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
      "kind": "object",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
      "kind": "object",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
      "kind": "object",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1263914-1784008649442382795.map",
  "pid": 1263914,
  "ppid": 1263813,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1263914-1784008649442382795.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1263987,
  "ppid": 1263965,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:94bacc1b1cb9860d:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
  "pid": 1263987,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:3de20f30d60b2b13:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "de3a810f0449f2d9c1a5c0cd7e8d1db2ce84ed52f80325630ae42da965180b8c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:35aef7f15eb03437:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "6457ad33bc75635b213f66f75855cd370f60bc50fcfb6c9d9e4415764849b2bc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:f25684b1d2f26abe:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "6d87ece02d10c59731f0a015b68bcb19b180924d92af602b715bfbdab531009d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:ab335e8970b9eded:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "951e6b338029412b3f70ecb4f4d490c83b5dd406ff20e01effc6b57f9991647f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:3982d6b76e4d0332:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "3a189547cce0a2808da4d2563a79efe9bd9ca5028b8337f217e906201a84cfe1",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:c8934e03f60b65e7:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "d8c1e2b5e4d20ff70df112a382fcf5287819135c658e98a090e5845a3e528374",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:e9b5ee1c8dd9b046:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "01f8a21ffe38cb9e46cc33f7e0ff90b8adf76856031e3820ecac21289749ff8d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "used:cc:1c565d9c528a0fe2:b8287218205100d3:48e0dc6e12ee4c06",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
  "pid": 1263987,
  "sha256": "e865daa118d163d5890f7d4c2459a04293edfdf83a2e3450deb537660ff06b47",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
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
  "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "cargo_pkg_name": "async-fs",
  "cargo_pkg_version": "1.6.0",
  "context_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1263987,
  "ppid": 1263965,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
    "/target/debug/build/async-fs-8ce5bb9be037c7a0",
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
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
      "kind": "object",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1263987-1784008649594802118.map",
  "pid": 1263987,
  "ppid": 1263965,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1263987-1784008649594802118.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
  "parsed_event_count": 60,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 61,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.087   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1263805 1263790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.098   rustc            1263806 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.121   rustc            1263813 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n0.121   rustc            1263816 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project_lite --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs --warn=clippy::undocumented_unsafe_blocks --warn=clippy::transmute_undefined_repr ...\n0.121   rustc            1263818 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"loom\")) -C metadata=9b0fbec01ca7cf60 ...\n0.122   rustc            1263820 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n0.122   rustc            1263822 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n0.123   rustc            1263824 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fastrand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.123   rustc            1263826 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name atomic_waker --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"portable-atomic\")) -C metadata=57514d67433289b8 ...\n0.123   rustc            1263828 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n0.124   rustc            1263832 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n0.125   rustc            1263833 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name waker_fn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"portable-atomic\", \"portable-atomic-util\")) -C metadata=8d43b10ac88413e9 ...\n0.126   rustc            1263834 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_task --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.126   rustc            1263835 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d2e563f9dbe0e981 ...\n0.127   rustc            1263836 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fastrand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=32de6853c0009f16 ...\n0.167   rustc            1263888 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_lite --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"fastrand\", \"futures-io\", \"memchr\", \"parking\", \"race\", \"std\")) -C metadata=0fa59264bcce38dd ...\n0.205   rustc            1263905 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_lock --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99d65c5d5b883523 ...\n0.247   cc               1263914 1263813   0 /tmp/native-trace-1263790-1784008647375/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.248   cc               1263915 1263914   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.251   collect2         1263922 1263915   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.251   rustc            1263921 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name piper --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"futures-io\" --cfg feature=\"std\" ...\n0.252   ld.lld           1263923 1263922   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911 ...\n0.253   rust-lld         1263923 1263922   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.310   build-script-bu  1263951 1263805   0 /target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build\n0.313   rustc            1263953 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n0.364   rustc            1263965 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e6d5eba148d07ec3 ...\n0.369   rustc            1263969 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_lite --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"fastrand\" ...\n0.399   cc               1263987 1263965   0 /tmp/native-trace-1263790-1784008647375/shims/cc -m64 /target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n0.400   cc               1263988 1263987   0 /usr/bin/cc -m64 /target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n0.402   collect2         1263989 1263988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.403   ld.lld           1263990 1263989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0 ...\n0.404   rust-lld         1263990 1263989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.446   build-script-bu  1264008 1263805   0 /target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build\n0.447   rustc            1264009 1264008   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n0.457   rustc            1264019 1264008   0 \n0.457   rustc            1264017 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name concurrent_queue --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"loom\", \"portable-atomic\", \"std\")) ...\n0.525   rustc            1264032 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(loom) --cfg feature=\"parking\" --cfg ...\n0.616   rustc            1264040 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener_strategy --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(wasm_bindgen_unstable_test_coverage) --cfg feature=\"std\" --check-cfg ...\n0.654   rustc            1264049 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_channel --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.725   rustc            1264056 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name blocking --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"tracing\")) -C metadata=cd694b3d5b5ed367 ...\n0.801   rustc            1264067 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_fs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=13885d42ed33b49a ...\n2.519   sh               1264114 2147557   0 /bin/sh -c which ps\n2.521   which            1264114 2147557   0 /usr/bin/which ps\n2.524   sh               1264115 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.525   ps               1264115 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.551   sh               1264116 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n2.552   cpuUsage.sh      1264116 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n2.554   sed              1264117 1264116   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n2.557   cat              1264118 1264116   0 /usr/bin/cat /proc/2240539/stat\n2.558   sleep            1264119 1264116   0 /usr/bin/sleep 1\n3.560   sed              1264120 1264116   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.563   cat              1264121 1264116   0 /usr/bin/cat /proc/2240539/stat\n4.456   16               1264123 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n4.470   frpc             1264123 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.009  runc             1264130 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4106687518 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n10.016  exe              1264137 1264130   0 /proc/self/exe init\n10.038  etcdctl          1264140 1264130   0 /usr/local/bin/etcdctl endpoint health\n15.740  runc             1264157 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1144082247 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.746  exe              1264164 1264157   0 /proc/self/exe init\n15.757  curl             1264166 1264157   0 /usr/bin/curl -f http://localhost:9091/healthz\n"
}
```

#### Record 25

```json
{
  "argv": [
    "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1263951,
  "build_script_target_dir": "crossbeam-utils-f32885586ba8a911",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build",
  "pid": 1263951,
  "ppid": 1263805,
  "root_cargo_pid": 1263805,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "_build_script_out_dir": "/target/debug/build/crossbeam-utils-f32885586ba8a911/out"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1264008,
  "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build",
  "pid": 1264008,
  "ppid": 1263805,
  "root_cargo_pid": 1263805,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_out_dir": "/target/debug/build/async-fs-8ce5bb9be037c7a0/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1264008,
  "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1264009,
  "ppid": 1264008,
  "root_cargo_pid": 1263805,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_out_dir": "/target/debug/build/async-fs-8ce5bb9be037c7a0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 1264008,
  "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 1264019,
  "ppid": 1264008,
  "root_cargo_pid": 1263805,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_build_script_out_dir": "/target/debug/build/async-fs-8ce5bb9be037c7a0/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 29

```json
{
  "crate": "crossbeam-utils",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "event_id": "bsrun:6b80ad835c841fcb:372f200b609cefb5:117f3b9a28a78f77",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
  "out_dir": "/target/debug/build/crossbeam-utils-f32885586ba8a911/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
  "success": true,
  "target": null,
  "version": "0.8.22",
  "_owner": {
    "crate": "crossbeam-utils",
    "version": "0.8.22",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
    "source": "cwd_prefix"
  }
}
```

#### Record 30

```json
{
  "crate": "async-fs",
  "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "event_id": "bsrun:75e05b4669246fe0:8bba6385259af248:2b7cbef40f6b2f3f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
  "out_dir": "/target/debug/build/async-fs-8ce5bb9be037c7a0/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
  "success": true,
  "target": null,
  "version": "1.6.0",
  "_owner": {
    "crate": "async-fs",
    "version": "1.6.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1264008,
  "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1264009,
  "ppid": 1264008,
  "root_cargo_pid": 1263805,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 32

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 1264008,
  "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
  "comm": "rustc",
  "event": "process_exec",
  "image": "rustc",
  "pid": 1264019,
  "ppid": 1264008,
  "root_cargo_pid": 1263805,
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
  "time": "2026-07-14T05:57:47.575123+00:00",
  "crate": "async-fs",
  "version": "1.6.0",
  "architecture": "ppc64le",
  "duration_seconds": 21.399220603052527,
  "trace_record_count": 30,
  "trace_owner_summary": {
    "owner_package_count": 29,
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
        "crate": "event-listener-strategy",
        "version": "0.5.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener-strategy@0.5.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4/Cargo.toml"
      },
      {
        "crate": "pin-project-lite",
        "version": "0.2.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml"
      },
      {
        "crate": "concurrent-queue",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml"
      },
      {
        "crate": "event-listener",
        "version": "2.5.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@2.5.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3/Cargo.toml"
      },
      {
        "crate": "event-listener",
        "version": "5.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@5.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1/Cargo.toml"
      },
      {
        "crate": "async-channel",
        "version": "2.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-channel@2.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0/Cargo.toml"
      },
      {
        "crate": "futures-core",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml"
      },
      {
        "crate": "futures-lite",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0/Cargo.toml"
      },
      {
        "crate": "atomic-waker",
        "version": "1.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/Cargo.toml"
      },
      {
        "crate": "futures-lite",
        "version": "2.6.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@2.6.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1/Cargo.toml"
      },
      {
        "crate": "futures-io",
        "version": "0.3.32",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.32",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/Cargo.toml"
      },
      {
        "crate": "async-lock",
        "version": "2.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-lock@2.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0/Cargo.toml"
      },
      {
        "crate": "async-task",
        "version": "4.7.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-task@4.7.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1/Cargo.toml"
      },
      {
        "crate": "blocking",
        "version": "1.6.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#blocking@1.6.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "1.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@1.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0/Cargo.toml"
      },
      {
        "crate": "fastrand",
        "version": "2.4.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml"
      },
      {
        "crate": "instant",
        "version": "0.1.13",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.13",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13/Cargo.toml"
      },
      {
        "crate": "waker-fn",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#waker-fn@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "parking",
        "version": "2.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking@2.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "piper",
        "version": "0.2.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#piper@0.2.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5/Cargo.toml"
      },
      {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "manifest_path": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 24,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "async-fs",
        "version": "1.6.0",
        "event_count": 15,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 9,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "event_count": 9,
        "kind_counts": {
          "exec": 1,
          "used_input": 4,
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
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-channel@2.5.0",
          "name": "async-channel",
          "version": "2.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
          "name": "async-fs",
          "version": "1.6.0",
          "manifest_path": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-lock@2.8.0",
          "name": "async-lock",
          "version": "2.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#async-task@4.7.1",
          "name": "async-task",
          "version": "4.7.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#atomic-waker@1.1.2",
          "name": "atomic-waker",
          "version": "1.1.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#blocking@1.6.2",
          "name": "blocking",
          "version": "1.6.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.4",
          "name": "cfg-if",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#concurrent-queue@2.5.0",
          "name": "concurrent-queue",
          "version": "2.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
          "name": "crossbeam-utils",
          "version": "0.8.22",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@2.5.3",
          "name": "event-listener",
          "version": "2.5.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener@5.4.1",
          "name": "event-listener",
          "version": "5.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#event-listener-strategy@0.5.4",
          "name": "event-listener-strategy",
          "version": "0.5.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@1.9.0",
          "name": "fastrand",
          "version": "1.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#fastrand@2.4.1",
          "name": "fastrand",
          "version": "2.4.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-core@0.3.32",
          "name": "futures-core",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-io@0.3.32",
          "name": "futures-io",
          "version": "0.3.32",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@1.13.0",
          "name": "futures-lite",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#futures-lite@2.6.1",
          "name": "futures-lite",
          "version": "2.6.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#instant@0.1.13",
          "name": "instant",
          "version": "0.1.13",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/instant-0.1.13"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#parking@2.2.1",
          "name": "parking",
          "version": "2.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pin-project-lite@0.2.17",
          "name": "pin-project-lite",
          "version": "0.2.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#piper@0.2.5",
          "name": "piper",
          "version": "0.2.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#waker-fn@1.2.0",
          "name": "waker-fn",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0"
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
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1263914,
      "ppid": 1263813,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "crossbeam-utils",
      "cargo_pkg_version": "0.8.22",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "event_id": "used:cc:798ba4f38ec52baf:fa58978e61434f9c:9448fe032432c550",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
      "pid": 1263914,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "crossbeam-utils",
      "cargo_pkg_version": "0.8.22",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "event_id": "used:cc:798ba4f38ec52baf:21b811b731cdea94:9448fe032432c550",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
      "pid": 1263914,
      "sha256": "7d84f9518dbf41ddad736e70480ba6fc99f6db7f73f24d33baed1f6abdd61500",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "crossbeam-utils",
      "cargo_pkg_version": "0.8.22",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "event_id": "used:cc:798ba4f38ec52baf:0040a6fc5ad76d66:9448fe032432c550",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
      "pid": 1263914,
      "sha256": "2b957730a597af89266d18dbc3c53a6794d59fc06c120ea8afcfd6bcaf69bdb1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "crossbeam-utils",
      "cargo_pkg_version": "0.8.22",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "event_id": "used:cc:798ba4f38ec52baf:9e1dd1d958bb46cb:9448fe032432c550",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
      "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
      "pid": 1263914,
      "sha256": "c626d4a76490e8a47df23077d3ce0e1a8f10d449dfa06fb23e7f0431455eb08a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
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
      "output": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "cargo_pkg_name": "crossbeam-utils",
      "cargo_pkg_version": "0.8.22",
      "context_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1263914,
      "ppid": 1263813,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z",
        "/target/debug/build/crossbeam-utils-f32885586ba8a911",
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
          "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z",
          "kind": "object",
          "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
          "kind": "object",
          "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
          "kind": "object",
          "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/crossbeam-utils-f32885586ba8a911",
          "kind": "object",
          "path": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1263914-1784008649442382795.map",
      "pid": 1263914,
      "ppid": 1263813,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1263914-1784008649442382795.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1263987,
      "ppid": 1263965,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:94bacc1b1cb9860d:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
      "pid": 1263987,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:3de20f30d60b2b13:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "de3a810f0449f2d9c1a5c0cd7e8d1db2ce84ed52f80325630ae42da965180b8c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:35aef7f15eb03437:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "6457ad33bc75635b213f66f75855cd370f60bc50fcfb6c9d9e4415764849b2bc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:f25684b1d2f26abe:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "6d87ece02d10c59731f0a015b68bcb19b180924d92af602b715bfbdab531009d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:ab335e8970b9eded:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "951e6b338029412b3f70ecb4f4d490c83b5dd406ff20e01effc6b57f9991647f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:3982d6b76e4d0332:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "3a189547cce0a2808da4d2563a79efe9bd9ca5028b8337f217e906201a84cfe1",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:c8934e03f60b65e7:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "d8c1e2b5e4d20ff70df112a382fcf5287819135c658e98a090e5845a3e528374",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:e9b5ee1c8dd9b046:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "01f8a21ffe38cb9e46cc33f7e0ff90b8adf76856031e3820ecac21289749ff8d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "used:cc:1c565d9c528a0fe2:b8287218205100d3:48e0dc6e12ee4c06",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
      "pid": 1263987,
      "sha256": "e865daa118d163d5890f7d4c2459a04293edfdf83a2e3450deb537660ff06b47",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
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
      "output": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "cargo_pkg_name": "async-fs",
      "cargo_pkg_version": "1.6.0",
      "context_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1263790-1784008647375/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1263987,
      "ppid": 1263965,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
        "/target/debug/build/async-fs-8ce5bb9be037c7a0",
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
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/async-fs-8ce5bb9be037c7a0",
          "kind": "object",
          "path": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libautocfg-9aa83b36beade1c9.rlib(autocfg-9aa83b36beade1c9.autocfg.37eb8a5a58c5ea64-cgu.4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1263987-1784008649594802118.map",
      "pid": 1263987,
      "ppid": 1263965,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1263987-1784008649594802118.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
      "parsed_event_count": 60,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 61,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.087   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1263805 1263790   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n0.098   rustc            1263806 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.121   rustc            1263813 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n0.121   rustc            1263816 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name pin_project_lite --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pin-project-lite-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::unused_trait_names --warn=unreachable_pub --warn=unnameable_types --warn=unexpected_cfgs --warn=clippy::undocumented_unsafe_blocks --warn=clippy::transmute_undefined_repr ...\n0.121   rustc            1263818 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking-2.2.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"loom\")) -C metadata=9b0fbec01ca7cf60 ...\n0.122   rustc            1263820 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_io --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-io-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n0.122   rustc            1263822 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-core-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n0.123   rustc            1263824 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fastrand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-2.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.123   rustc            1263826 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name atomic_waker --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/atomic-waker-1.1.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"portable-atomic\")) -C metadata=57514d67433289b8 ...\n0.123   rustc            1263828 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=34a4553e3b7e20ea ...\n0.124   rustc            1263832 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"std\" ...\n0.125   rustc            1263833 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name waker_fn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/waker-fn-1.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"portable-atomic\", \"portable-atomic-util\")) -C metadata=8d43b10ac88413e9 ...\n0.126   rustc            1263834 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_task --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-task-4.7.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.126   rustc            1263835 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-2.5.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d2e563f9dbe0e981 ...\n0.127   rustc            1263836 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name fastrand --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/fastrand-1.9.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=32de6853c0009f16 ...\n0.167   rustc            1263888 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_lite --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-2.6.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"alloc\", \"default\", \"fastrand\", \"futures-io\", \"memchr\", \"parking\", \"race\", \"std\")) -C metadata=0fa59264bcce38dd ...\n0.205   rustc            1263905 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_lock --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-lock-2.8.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=99d65c5d5b883523 ...\n0.247   cc               1263914 1263813   0 /tmp/native-trace-1263790-1784008647375/shims/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.248   cc               1263915 1263914   0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-f32885586ba8a911/rustcE28p5z/symbols.o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.build_script_build.7f47a97863c05426-cgu /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911.80mhn01ipw3pmuziy88mdvk4t.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.251   collect2         1263922 1263915   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.251   rustc            1263921 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name piper --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/piper-0.2.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"futures-io\" --cfg feature=\"std\" ...\n0.252   ld.lld           1263923 1263922   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-f32885586ba8a911/build_script_build-f32885586ba8a911 ...\n0.253   rust-lld         1263923 1263922   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccb2QLmx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.310   build-script-bu  1263951 1263805   0 /target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build\n0.313   rustc            1263953 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n0.364   rustc            1263965 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=e6d5eba148d07ec3 ...\n0.369   rustc            1263969 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_lite --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-lite-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"fastrand\" ...\n0.399   cc               1263987 1263965   0 /tmp/native-trace-1263790-1784008647375/shims/cc -m64 /target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n0.400   cc               1263988 1263987   0 /usr/bin/cc -m64 /target/debug/build/async-fs-8ce5bb9be037c7a0/rustcSRb3ir/symbols.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.16a47pt3qzl0yly81pg8qpeup.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7f3n5s7ellgjp1wlfc47uhclq.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tyv6kvyuib0si03o84x2bd0i.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.8zdfdt04pi249whl1l6ys91jg.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9mo4qe6ec6ra5lbxhpg90w5d2.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.9zbgg32q11f6dey68a0wc6w54.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.ae9gez3odpxdwlug7ze9ke5sl.1kfcl85.rcgu.o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0.7tk0mod6o0j1gbe0uagt2s0hv.1kfcl85.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a ...\n0.402   collect2         1263989 1263988   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.403   ld.lld           1263990 1263989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/async-fs-8ce5bb9be037c7a0/build_script_build-8ce5bb9be037c7a0 ...\n0.404   rust-lld         1263990 1263989   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cciipMZ4.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.446   build-script-bu  1264008 1263805   0 /target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build\n0.447   rustc            1264009 1264008   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n0.457   rustc            1264019 1264008   0 \n0.457   rustc            1264017 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name concurrent_queue --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/concurrent-queue-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"std\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"loom\", \"portable-atomic\", \"std\")) ...\n0.525   rustc            1264032 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-5.4.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(loom) --cfg feature=\"parking\" --cfg ...\n0.616   rustc            1264040 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name event_listener_strategy --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/event-listener-strategy-0.5.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(wasm_bindgen_unstable_test_coverage) --cfg feature=\"std\" --check-cfg ...\n0.654   rustc            1264049 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_channel --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/async-channel-2.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.725   rustc            1264056 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name blocking --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/blocking-1.6.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"tracing\")) -C metadata=cd694b3d5b5ed367 ...\n0.801   rustc            1264067 1263805   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name async_fs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=13885d42ed33b49a ...\n2.519   sh               1264114 2147557   0 /bin/sh -c which ps\n2.521   which            1264114 2147557   0 /usr/bin/which ps\n2.524   sh               1264115 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.525   ps               1264115 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n2.551   sh               1264116 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n2.552   cpuUsage.sh      1264116 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n2.554   sed              1264117 1264116   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n2.557   cat              1264118 1264116   0 /usr/bin/cat /proc/2240539/stat\n2.558   sleep            1264119 1264116   0 /usr/bin/sleep 1\n3.560   sed              1264120 1264116   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.563   cat              1264121 1264116   0 /usr/bin/cat /proc/2240539/stat\n4.456   16               1264123 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n4.470   frpc             1264123 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.009  runc             1264130 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process4106687518 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n10.016  exe              1264137 1264130   0 /proc/self/exe init\n10.038  etcdctl          1264140 1264130   0 /usr/local/bin/etcdctl endpoint health\n15.740  runc             1264157 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1144082247 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.746  exe              1264164 1264157   0 /proc/self/exe init\n15.757  curl             1264166 1264157   0 /usr/bin/curl -f http://localhost:9091/healthz\n"
    },
    {
      "argv": [
        "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1263951,
      "build_script_target_dir": "crossbeam-utils-f32885586ba8a911",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build",
      "pid": 1263951,
      "ppid": 1263805,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1264008,
      "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build",
      "pid": 1264008,
      "ppid": 1263805,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1264008,
      "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1264009,
      "ppid": 1264008,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 1264008,
      "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 1264019,
      "ppid": 1264008,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "crossbeam-utils",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "event_id": "bsrun:6b80ad835c841fcb:372f200b609cefb5:117f3b9a28a78f77",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/crossbeam-utils-f32885586ba8a911/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
      "out_dir": "/target/debug/build/crossbeam-utils-f32885586ba8a911/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
      "success": true,
      "target": null,
      "version": "0.8.22",
      "_owner": {
        "crate": "crossbeam-utils",
        "version": "0.8.22",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.22",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "async-fs",
      "cwd": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "event_id": "bsrun:75e05b4669246fe0:8bba6385259af248:2b7cbef40f6b2f3f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/async-fs-8ce5bb9be037c7a0/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
      "out_dir": "/target/debug/build/async-fs-8ce5bb9be037c7a0/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
      "success": true,
      "target": null,
      "version": "1.6.0",
      "_owner": {
        "crate": "async-fs",
        "version": "1.6.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0#async-fs@1.6.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-k29p6cv6/src/async-fs-1.6.0",
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
      "build_script_root_pid": 1264008,
      "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1264009,
      "ppid": 1264008,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 1264008,
      "build_script_target_dir": "async-fs-8ce5bb9be037c7a0",
      "comm": "rustc",
      "event": "process_exec",
      "image": "rustc",
      "pid": 1264019,
      "ppid": 1264008,
      "root_cargo_pid": 1263805,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1165,
    "crate": "async-fs",
    "version": "1.6.0",
    "crate_id": "133285",
    "version_id": "604596",
    "downloads": 16499517,
    "cumulative_downloads": 92518818265,
    "cumulative_share_of_global": 0.3459065029856258,
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
