# `num-traits` `0.2.19`

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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
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
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb",
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
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-4891-1783992596014221281.map",
  "pid": 4891,
  "ppid": 4839,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-4891-1783992596014221281.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "workspace_root": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
      "name": "autocfg",
      "version": "1.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
      "name": "num-traits",
      "version": "0.2.19",
      "manifest_path": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19"
    }
  ],
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "exit_code": 0,
  "kind": "exec",
  "pid": 4891,
  "ppid": 4839,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:03a181ce34642e55:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
  "pid": 4891,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:36b40c91448728eb:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "737428d9c5fb6755226f73957a6888a5002c8fc575d6b20d0449a49fb8bbe96a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:445ef015cee9da8c:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "2b3a03ca513a0d277da4d1183584443335aa62175babd314916d0f702225e73d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:f2e2d3177f583bd9:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "4c3a9172c02a2d6be84ed71cefa95fa5ca50bcfd49b3fb9e1f6e9940f9d21334",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:be583e2c15635b30:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "1f85e44719fc7686eb5826339ea1a2a0b2b8286551f2977082aeffaf56cb7320",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:6e6e71d18e8ab021:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "7e9adf1e120c78d160df9b00808887ecd24178711a3e2bb0d17de44eb0094538",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "used:cc:2f77bd425cc719cf:ab70f90ec14d7f21:967fc3ae76813152",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
  "pid": 4891,
  "sha256": "d53ba55177bfbf4cef00e728305a19e4ca3104206ee5b6223397d56b605a9200",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
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
  "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "cargo_pkg_name": "num-traits",
  "cargo_pkg_version": "0.2.19",
  "context_path": "/tmp/native-trace-3361-1783992591488/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-3361-1783992591488/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 4891,
  "ppid": 4839,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
    "/target/debug/build/num-traits-5f67c9ba029d8bfb",
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
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
      "kind": "object",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-4891-1783992596014221281.map",
  "pid": 4891,
  "ppid": 4839,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-4891-1783992596014221281.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 13

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

#### Record 14

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 393,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 394,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.354   ld.lld           5168   5166     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccloKj5q.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n1.357   rust-lld         5168   5166     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccloKj5q.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.363   collect2         5171   5163     0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.366   ld.lld           5172   5171     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n1.373   rust-lld         5172   5171     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.406   build-script-bu  5202   4440     0 /target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build\n1.417   rustc            5207   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.446   rustc            5238   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_de716bda1ec6b2df_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/num-traits-93d6467c1e35fcf1/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.446   rustc            5229   4127     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.475   build-script-bu  5281   4514     0 /target/debug/build/generic-array-eebdc96a43b62923/build-script-build\n1.482   rustc            5282   5281     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n1.491   rustc            5271   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_de716bda1ec6b2df_1 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/num-traits-93d6467c1e35fcf1/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.518   build-script-bu  5334   4693     0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n1.529   rustc            5343   4660     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=26a05e840352c101 ...\n1.540   rustc            5365   4440     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.548   rustc            5373   5334     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n1.558   rustc            5374   4938     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=bc175e305027093f ...\n1.558   rustc            5383   5378     0 \n1.558   build-script-bu  5378   4693     0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n1.563   rustc            5386   4594     0 \n1.563   rustc            5387   3810     0 \n1.591   rustc            5413   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span.rs --target powerpc64le-unknown-linux-gnu\n1.605   cc               5430   4912     0 /tmp/native-trace-3564-1783992591752/shims/cc -m64 /target/debug/build/syn-8e197ea489f52d3e/rustcRgej83/symbols.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.0utolxp0p2pr44go2erztto30.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1cvrgnm4obgk14yqlqunqjp4u.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1xzkq3bhi1eo57mr89b2k2gb9.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1ylnp7qbg1r9zjnqcfkjawbvx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.2am004887au5osqtz6ib2utu4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.39pcw8ibwr05y8m8eou11jovl.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3c9zc3un96k1q15lwciixlgr4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3lwtlrtlmwrq3p6hed3ie11bx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3mrl5htmfdamw7o28crx7t481.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4g5m3arf4j3qab9h1d1yo3c8g.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4ih3np50ahfabpkbbfogq3v1w.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4led5rdgn4cyftqptg9usmbti.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4vhof8f02be7dedkn4i39trv3.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.57ooxrgnjzahndwxakbpl0bp2.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5avj5ojvlrxrs6loajwqhmjp1.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5byrf5g503fxkucanzs7j5p9i.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5icz551fby0q1pd8c0nhgfcra.18amxsk.rcgu.o ...\n1.607   cc               5465   5430     0 /usr/bin/cc -m64 /target/debug/build/syn-8e197ea489f52d3e/rustcRgej83/symbols.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.0utolxp0p2pr44go2erztto30.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1cvrgnm4obgk14yqlqunqjp4u.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1xzkq3bhi1eo57mr89b2k2gb9.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1ylnp7qbg1r9zjnqcfkjawbvx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.2am004887au5osqtz6ib2utu4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.39pcw8ibwr05y8m8eou11jovl.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3c9zc3un96k1q15lwciixlgr4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3lwtlrtlmwrq3p6hed3ie11bx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3mrl5htmfdamw7o28crx7t481.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4g5m3arf4j3qab9h1d1yo3c8g.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4ih3np50ahfabpkbbfogq3v1w.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4led5rdgn4cyftqptg9usmbti.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4vhof8f02be7dedkn4i39trv3.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.57ooxrgnjzahndwxakbpl0bp2.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5avj5ojvlrxrs6loajwqhmjp1.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5byrf5g503fxkucanzs7j5p9i.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5icz551fby0q1pd8c0nhgfcra.18amxsk.rcgu.o ...\n1.617   cc               5474   5374     0 /tmp/native-trace-3651-1783992591802/shims/cc -m64 /target/debug/build/generic-array-eebdc96a43b62923/rustcK5vBGB/symbols.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.33rqti0twnljaal5gi3eqrfkf.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.40ff4s62sl94aqjv6hkvchqir.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.7gtagoq1mqx9dyc96i49liaqs.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9epedn978speey25kflorm7zb.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9gm58v6adhcipgd4b1k8x8unx.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.du5wr0iok2zts0klc6lsqsf1k.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.0nm09f1jy09ysunc6nvd6fw9i.1lhfidy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n1.620   cc               5484   5474     0 /usr/bin/cc -m64 /target/debug/build/generic-array-eebdc96a43b62923/rustcK5vBGB/symbols.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.33rqti0twnljaal5gi3eqrfkf.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.40ff4s62sl94aqjv6hkvchqir.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.7gtagoq1mqx9dyc96i49liaqs.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9epedn978speey25kflorm7zb.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9gm58v6adhcipgd4b1k8x8unx.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.du5wr0iok2zts0klc6lsqsf1k.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.0nm09f1jy09ysunc6nvd6fw9i.1lhfidy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n1.627   collect2         5486   5484     0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.627   cc               5489   5482     0 \n1.627   cc               5482   5343     0 /tmp/native-trace-3544-1783992591732/shims/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcxhvl5C/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1t1p6t8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.627   ld.lld           5490   5486     0 \n1.633   rust-lld         5490   5486     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923 ...\n1.633   collect2         5492   5489     0 \n1.633   ld.lld           5494   5492     0 \n1.634   rust-lld         5494   5492     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsQpEnh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsQpEnh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b ...\n1.636   rustc            5483   4004     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.643   collect2         5496   5465     0 \n1.645   ld.lld           5497   5496     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4mFVCq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e ...\n1.648   rust-lld         5497   5496     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4mFVCq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.651   cc               5469   5386     0 /tmp/native-trace-3368-1783992591509/shims/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcMOwZyj/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1wl5rva.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.664   rustc            5518   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_location.rs --target powerpc64le-unknown-linux-gnu\n1.682   cc               5554   5044     0 /tmp/native-trace-3456-1783992591583/shims/cc -m64 /target/debug/build/winapi-78719dd133b3c578/rustcYqMwGs/symbols.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.00ps6htrb975kmbwit7zq3loq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.05op9ji5t4noqkqwgjcyc8zpg.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0lxsobseykngncfa2k11t73hd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0sghx1ve4q9n3mx22tsudkstr.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.16m2820sfqbhi88heaqm6a5yn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.1egcam2my8954zdhbi27q6zxq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.21en0u2i5akvfaz16vbwt8wm2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.24i73zywcmco89bn2f5zo74qw.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2i6mlqmgl4l3o6v6t4wsz3vcd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2td99tt2qqg53jrjmilye4lw2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2tvim9d3kdgg3i84ljbkikptn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2z2ydgxo7y24144vhskejuk7f.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.337dcr78zn3jlr36fpqfnlr4a.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33s8pn2tvxtf1e1ugfilm09z9.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33uuzuyaino25uv0g5s6piu1k.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.3nx8muhgyh0vlnp97exzal8fd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.49tkm7hbt7bct5uz00s6on54s.1nsx7ue.rcgu.o ...\n1.696   cc               5565   5554     0 /usr/bin/cc -m64 /target/debug/build/winapi-78719dd133b3c578/rustcYqMwGs/symbols.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.00ps6htrb975kmbwit7zq3loq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.05op9ji5t4noqkqwgjcyc8zpg.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0lxsobseykngncfa2k11t73hd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0sghx1ve4q9n3mx22tsudkstr.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.16m2820sfqbhi88heaqm6a5yn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.1egcam2my8954zdhbi27q6zxq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.21en0u2i5akvfaz16vbwt8wm2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.24i73zywcmco89bn2f5zo74qw.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2i6mlqmgl4l3o6v6t4wsz3vcd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2td99tt2qqg53jrjmilye4lw2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2tvim9d3kdgg3i84ljbkikptn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2z2ydgxo7y24144vhskejuk7f.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.337dcr78zn3jlr36fpqfnlr4a.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33s8pn2tvxtf1e1ugfilm09z9.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33uuzuyaino25uv0g5s6piu1k.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.3nx8muhgyh0vlnp97exzal8fd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.49tkm7hbt7bct5uz00s6on54s.1nsx7ue.rcgu.o ...\n1.708   collect2         5569   5565     0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.710   rustc            5568   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_file.rs --target powerpc64le-unknown-linux-gnu\n1.720   cc               5521   5469     0 /usr/bin/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcMOwZyj/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1wl5rva.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.725   collect2         5574   5521     0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.730   ld.lld           5570   5569     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578 ...\n1.730   git              5571   2235138   0 /usr/bin/git blame --root --incremental d3531d3cf8139d4faf98563bb286db3f509aca5c -- native-trace/install_native_trace_tools_static.sh\n1.730   ld.lld           5577   5574     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b ...\n1.731   rust-lld         5577   5574     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.737   build-script-bu  5579   4660     0 /target/debug/build/indexmap-d08c601bd9bf6f9b/build-script-build\n1.741   rust-lld         5570   5569     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.741   rustc            5580   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.766   build-script-bu  5602   4938     0 /target/debug/build/generic-array-eebdc96a43b62923/build-script-build\n1.775   rustc            5606   5602     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n1.778   rustc            5603   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_7adc6dbd9212bf83_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/indexmap-04414cb891c879d8/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.780   rustc            5605   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.823   build-script-bu  5637   4693     0 /target/debug/build/syn-8e197ea489f52d3e/build-script-build\n1.828   rustc            5636   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_7adc6dbd9212bf83_1 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/indexmap-04414cb891c879d8/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.831   rustc            5638   5637     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n1.852   build-script-bu  5650   4594     0 \n1.852   rustc            5646   3810     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.858   rustc            5651   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.871   rustc            5654   4660     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=03fb2f105f8b1dc2 ...\n1.881   rustc            5657   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_219ecca48109228b_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/indexmap-9467ba935f76af73/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.896   rustc            5668   4004     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.918   rustc            5679   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_219ecca48109228b_1 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/indexmap-9467ba935f76af73/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.940   rustc            5683   4514     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=957247ca69051b50 ...\n1.956   rustc            5696   4594     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=0ac8973ac28aad7f ...\n1.994   build-script-bu  5701   4949     0 /target/debug/build/winapi-78719dd133b3c578/build-script-build\n2.012   rustc            5703   4949     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winapi --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\" -C metadata=7d34a9d34ec8fbb2 ...\n2.092   git              5711   2235138   0 /usr/bin/git worktree list --porcelain\n2.111   rustc            5715   4938     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=7005c0eb561d969d ...\n2.172   rustc            5723   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n2.338   rustc            5779   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n3.076   sh               5888   2147557   0 /bin/sh -c which ps\n3.078   which            5888   2147557   0 /usr/bin/which ps\n3.080   sh               5889   2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.082   ps               5889   2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.106   sh               5892   2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.108   cpuUsage.sh      5892   2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 4193774 4193798 4193802 4193840 4193952 4193989 4194042 4194079 4194109 4194137 4194157 4194167 4194173\n3.110   sed              5893   5892     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.112   cat              5894   5892     0 /usr/bin/cat /proc/2240539/stat\n3.114   cat              5895   5892     0 /usr/bin/cat /proc/4193716/stat\n3.115   cat              5896   5892     0 /usr/bin/cat /proc/4193774/stat\n3.117   cat              5897   5892     0 /usr/bin/cat /proc/4193798/stat\n3.118   cat              5900   5892     0 /usr/bin/cat /proc/4193802/stat\n3.120   cat              5901   5892     0 /usr/bin/cat /proc/4193840/stat\n3.121   cat              5902   5892     0 /usr/bin/cat /proc/4193952/stat\n3.123   cat              5903   5892     0 /usr/bin/cat /proc/4193989/stat\n3.124   cat              5904   5892     0 /usr/bin/cat /proc/4194042/stat\n3.126   cat              5905   5892     0 /usr/bin/cat /proc/4194079/stat\n3.127   cat              5906   5892     0 /usr/bin/cat /proc/4194109/stat\n3.129   cat              5907   5892     0 /usr/bin/cat /proc/4194137/stat\n3.130   cat              5908   5892     0 /usr/bin/cat /proc/4194157/stat\n3.131   cat              5909   5892     0 /usr/bin/cat /proc/4194167/stat\n3.133   cat              5910   5892     0 /usr/bin/cat /proc/4194173/stat\n3.134   sleep            5911   5892     0 /usr/bin/sleep 1\n4.137   sed              6401   5892     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.140   cat              6402   5892     0 /usr/bin/cat /proc/2240539/stat\n4.141   cat              6404   5892     0 /usr/bin/cat /proc/4193716/stat\n4.143   cat              6406   5892     0 /usr/bin/cat /proc/4193774/stat\n4.145   cat              6408   5892     0 /usr/bin/cat /proc/4193798/stat\n4.147   cat              6410   5892     0 /usr/bin/cat /proc/4193802/stat\n4.149   cat              6412   5892     0 /usr/bin/cat /proc/4193840/stat\n4.151   cat              6414   5892     0 /usr/bin/cat /proc/4193952/stat\n4.153   cat              6416   5892     0 /usr/bin/cat /proc/4193989/stat\n4.154   cat              6418   5892     0 /usr/bin/cat /proc/4194042/stat\n4.156   cat              6420   5892     0 /usr/bin/cat /proc/4194079/stat\n4.158   cat              6422   5892     0 /usr/bin/cat /proc/4194109/stat\n4.160   cat              6424   5892     0 /usr/bin/cat /proc/4194137/stat\n4.161   cat              6426   5892     0 /usr/bin/cat /proc/4194157/stat\n4.163   cat              6428   5892     0 /usr/bin/cat /proc/4194167/stat\n4.165   cat              6430   5892     0 /usr/bin/cat /proc/4194173/stat\n4.238   runc             6432   4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1973706304 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n4.243   exe              6439   6432     0 /proc/self/exe init\n4.265   curl             6442   6432     0 /usr/bin/curl -f http://localhost:9091/healthz\n8.870   16               6449   1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n8.872   16               6450   1        0 /proc/self/fd/16 --deserialize 138 --log-level info --log-target journal-or-kmsg\n8.886   frpc             6449   1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n8.891   sa1              6450   1        0 /usr/lib64/sa/sa1 1 1\n8.894   sadc             6450   1        0 /usr/lib64/sa/sadc -F -L -S DISK 1 1 /var/log/sa\n10.893  16               6459   1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n10.897  16               6460   1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n11.068  systemd-coredum  6459   1        0 /usr/lib/systemd/systemd-coredump\n11.069  drkonqi-coredum  6460   1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 880-6458-0\n11.193  runc             6468   3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process3389782033 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n11.200  exe              6478   6468     0 /proc/self/exe init\n11.227  curl             6480   6468     0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n11.625  9                6487   4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n11.626  abrt-server      6486   1118     0 /usr/bin/abrt-server -s\n11.641  drkonqi-coredum  6487   4003047   0 /usr/libexec/drkonqi-coredump-launcher\n11.657  abrt-handle-eve  6488   6486     0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:30:06.646999-4193631\n11.673  sh               6491   6488     0 /bin/sh -c abrt-action-save-package-data\\n\n11.675  abrt-action-sav  6491   6488     0 /usr/bin/abrt-action-save-package-data\n11.738  sh               6494   6488     0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n11.740  cut              6496   6494     0 /usr/bin/cut -d: -f1\n11.740  cat              6497   6495     0 /usr/bin/cat uid\n11.742  getent           6495   6494     0 /usr/bin/getent passwd 1000\n11.744  lscpu            6498   6494     0 /usr/bin/lscpu\n11.760  sh               6499   6488     0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n11.762  runlevel         6500   6499     0 /usr/bin/runlevel\n11.774  sh               6501   6488     0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n11.776  grep             6502   6501     0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n11.778  grep             6503   6501     0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n11.779  grep             6504   6501     0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n11.781  abrt-action-cor  6505   6501     0 /usr/libexec/abrt-action-coredump -x\n11.849  abrt-action-gen  6506   6501     0 /usr/bin/abrt-action-generate-core-backtrace\n11.907  abrt-action-ana  6507   6501     0 /usr/bin/abrt-action-analyze-vulnerability\n11.909  eu-readelf       6509   6508     0 /usr/bin/eu-readelf -n coredump\n11.910  grep             6510   6508     0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n11.910  sed              6511   6508     0 /usr/bin/sed s/[^0-9]//g\n11.913  gdb              6513   6512     0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n11.930  iconv            6514   6513     0 /usr/bin/iconv -l\n12.039  abrt-action-ana  6523   6501     0 /usr/bin/abrt-action-analyze-c\n12.054  eu-unstrip       6524   6523     0 /usr/bin/eu-unstrip --core=./coredump -n\n12.073  abrt-action-lis  6525   6501     0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n12.143  cat              6527   6526     0 /usr/bin/cat executable\n12.144  cat              6528   6526     0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:30:06.646999-4193631/uid\n12.146  journalctl       6529   6526     0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n12.160  abrt-action-cor  6530   6501     0 /usr/libexec/abrt-action-coredump -r\n12.221  abrt-handle-eve  6531   6486     0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.237  sh               6532   6531     0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n12.239  dbus-send        6532   6531     0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.242  sh               6533   6531     0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n12.243  abrt-action-not  6534   6533     0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.314  sh               6535   6534     0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n12.315  reporter-system  6535   6534     0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.289  runc             6539   2454     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c --log-format json --systemd-cgroup kill --all a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd 9\n17.311  runc             6546   2454     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c --log-format json --systemd-cgroup delete a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd\n17.477  containerd-shim  6552   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c delete\n17.480  runc             6558   6552     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04c --log-format json delete --force a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd\n17.516  runc             6564   1148     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 --log-format json --systemd-cgroup kill --all 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17 9\n17.525  runc             6573   1148     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 --log-format json --systemd-cgroup delete 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17\n17.529  sh               6580   6570     0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethb1d16a9\n17.531  ethtool          6581   6580     0 /usr/sbin/ethtool -i vethb1d16a9\n17.531  sed              6582   6580     0 /usr/bin/sed -n s/^driver: //p\n17.539  systemd-sysctl   6585   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb1d16a9 --prefix=/net/ipv4/neigh/vethb1d16a9 --prefix=/net/ipv6/conf/vethb1d16a9 --prefix=/net/ipv6/neigh/vethb1d16a9\n17.719  containerd-shim  6591   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 delete\n17.722  runc             6598   6591     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb1 --log-format json delete --force 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17\n17.764  systemd-sysctl   6603   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth706ab07 --prefix=/net/ipv4/neigh/veth706ab07 --prefix=/net/ipv6/conf/veth706ab07 --prefix=/net/ipv6/neigh/veth706ab07\n17.853  runc             6606   775      0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 --log-format json --systemd-cgroup kill --all c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403 9\n17.861  runc             6612   775      0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 --log-format json --systemd-cgroup delete c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403\n18.079  containerd-shim  6618   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 delete\n18.083  runc             6625   6618     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f13240 --log-format json delete --force c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403\n18.121  systemd-sysctl   6630   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6de20b5 --prefix=/net/ipv4/neigh/veth6de20b5 --prefix=/net/ipv6/conf/veth6de20b5 --prefix=/net/ipv6/neigh/veth6de20b5\n18.278  sh               6631   2147557   0 /bin/sh -c which ps\n18.279  which            6631   2147557   0 /usr/bin/which ps\n18.282  sh               6632   2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.283  ps               6632   2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.314  sh               6633   2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.316  cpuUsage.sh      6633   2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 4193798 4193802 4193840 4193952 4193989 4194042 4194079 4194109 4194137 4194157 4194167 4194173\n18.318  sed              6634   6633     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.321  cat              6635   6633     0 /usr/bin/cat /proc/2240539/stat\n18.322  cat              6636   6633     0 /usr/bin/cat /proc/4193716/stat\n18.324  cat              6637   6633     0 /usr/bin/cat /proc/4193798/stat\n18.325  cat              6638   6633     0 /usr/bin/cat /proc/4193802/stat\n18.326  cat              6639   6633     0 /usr/bin/cat /proc/4193840/stat\n18.328  cat              6640   6633     0 /usr/bin/cat /proc/4193952/stat\n18.329  cat              6641   6633     0 /usr/bin/cat /proc/4193989/stat\n18.331  cat              6642   6633     0 /usr/bin/cat /proc/4194042/stat\n18.332  cat              6644   6633     0 /usr/bin/cat /proc/4194079/stat\n18.334  runc             6646   2898     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e --log-format json --systemd-cgroup kill --all 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496 9\n18.334  cat              6645   6633     0 /usr/bin/cat /proc/4194109/stat\n18.335  cat              6647   6633     0 /usr/bin/cat /proc/4194137/stat\n18.337  cat              6653   6633     0 /usr/bin/cat /proc/4194157/stat\n18.338  cat              6654   6633     0 /usr/bin/cat /proc/4194167/stat\n18.340  cat              6655   6633     0 /usr/bin/cat /proc/4194173/stat\n18.341  sleep            6656   6633     0 /usr/bin/sleep 1\n18.344  runc             6657   2898     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e --log-format json --systemd-cgroup delete 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496\n18.512  runc             6663   1313     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d --log-format json --systemd-cgroup kill --all b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a 9\n18.520  runc             6669   1313     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d --log-format json --systemd-cgroup delete b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a\n18.541  containerd-shim  6676   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e delete\n18.544  runc             6683   6676     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e49 --log-format json delete --force 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496\n18.593  systemd-sysctl   6688   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth97936d7 --prefix=/net/ipv4/neigh/veth97936d7 --prefix=/net/ipv6/conf/veth97936d7 --prefix=/net/ipv6/neigh/veth97936d7\n18.719  containerd-shim  6689   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d delete\n18.722  runc             6696   6689     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713 --log-format json delete --force b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a\n18.765  systemd-sysctl   6701   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth865c014 --prefix=/net/ipv4/neigh/veth865c014 --prefix=/net/ipv6/conf/veth865c014 --prefix=/net/ipv6/neigh/veth865c014\n19.119  runc             6703   3108     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e --log-format json --systemd-cgroup kill --all 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1 9\n19.127  runc             6709   3108     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e --log-format json --systemd-cgroup delete 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1\n19.326  containerd-shim  6716   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e delete\n19.329  runc             6722   6716     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c --log-format json delete --force 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1\n19.343  sed              6728   6633     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.346  cat              6729   6633     0 /usr/bin/cat /proc/2240539/stat\n19.348  cat              6731   6633     0 /usr/bin/cat /proc/4193716/stat\n19.350  cat              6733   6633     0 /usr/bin/cat /proc/4193798/stat\n19.353  cat              6736   6633     0 /usr/bin/cat /proc/4193840/stat\n19.355  cat              6738   6633     0 /usr/bin/cat /proc/4193952/stat\n19.357  cat              6741   6633     0 /usr/bin/cat /proc/4194042/stat\n19.359  cat              6743   6633     0 /usr/bin/cat /proc/4194079/stat\n19.361  cat              6745   6633     0 /usr/bin/cat /proc/4194109/stat\n19.363  cat              6747   6633     0 /usr/bin/cat /proc/4194137/stat\n19.364  systemd-sysctl   6748   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0432ce7 --prefix=/net/ipv4/neigh/veth0432ce7 --prefix=/net/ipv6/conf/veth0432ce7 --prefix=/net/ipv6/neigh/veth0432ce7\n19.365  cat              6750   6633     0 /usr/bin/cat /proc/4194157/stat\n19.368  cat              6752   6633     0 /usr/bin/cat /proc/4194167/stat\n19.369  cat              6754   6633     0 /usr/bin/cat /proc/4194173/stat\n19.379  runc             6756   2967     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bc --log-format json --systemd-cgroup kill --all 71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bce66fb 9\n19.388  runc             6763   2967     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bc --log-format json --systemd-cgroup delete 71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bce66fb\n19.398  runc             6769   1762     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b3426 --log-format json --systemd-cgroup kill --all 98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b34269c5fc 9\n19.416  runc             6775   3238     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c30785357 --log-format json --systemd-cgroup kill --all 0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c3078535752656 9\n19.417  runc             6776   1762     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b3426 --log-format json --systemd-cgroup delete 98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b34269c5fc\n19.427  runc             6787   3125     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f --log-format json --systemd-cgroup kill --all 152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f804ad 9\n19.435  runc             6793   3238     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c30785357 --log-format json --systemd-cgroup delete 0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c3078535752656\n19.440  runc             6799   3125     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f --log-format json --systemd-cgroup delete 152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f804ad\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build",
  "pid": 5022,
  "ppid": 4127,
  "root_cargo_pid": 4127,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out"
}
```

#### Record 16

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5023,
  "ppid": 5022,
  "root_cargo_pid": 4127,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_83d94a365f7abd21_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5057,
  "ppid": 5022,
  "root_cargo_pid": 4127,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_83d94a365f7abd21_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5101,
  "ppid": 5022,
  "root_cargo_pid": 4127,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_build_script_out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "num-traits",
  "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "event_id": "bsrun:89e44160041aa890:6cf91e0194f74cbf:d06da07181363fb6",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
  "out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
  "success": true,
  "target": null,
  "version": "0.2.19",
  "_owner": {
    "crate": "num-traits",
    "version": "0.2.19",
    "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
    "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
    "source": "cwd_prefix"
  }
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5023,
  "ppid": 5022,
  "root_cargo_pid": 4127,
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
    "--crate-name",
    "autocfg_83d94a365f7abd21_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5057,
  "ppid": 5022,
  "root_cargo_pid": 4127,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 22

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_83d94a365f7abd21_1",
    "--crate-type=lib",
    "--out-dir",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
    "--emit=llvm-ir",
    "--target",
    "powerpc64le-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 5022,
  "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 5101,
  "ppid": 5022,
  "root_cargo_pid": 4127,
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
  "time": "2026-07-14T01:30:15.335398+00:00",
  "crate": "num-traits",
  "version": "0.2.19",
  "architecture": "ppc64le",
  "duration_seconds": 32.547217248007655,
  "trace_record_count": 19,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "manifest_path": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 6,
    "owners": [
      {
        "crate": "num-traits",
        "version": "0.2.19",
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
      }
    ]
  },
  "trace_records": [
    {
      "event": "native_trace_root_context",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "workspace_root": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
          "name": "autocfg",
          "version": "1.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
          "name": "num-traits",
          "version": "0.2.19",
          "manifest_path": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19"
        }
      ],
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "exit_code": 0,
      "kind": "exec",
      "pid": 4891,
      "ppid": 4839,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:03a181ce34642e55:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
      "pid": 4891,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:36b40c91448728eb:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "737428d9c5fb6755226f73957a6888a5002c8fc575d6b20d0449a49fb8bbe96a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:445ef015cee9da8c:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "2b3a03ca513a0d277da4d1183584443335aa62175babd314916d0f702225e73d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:f2e2d3177f583bd9:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "4c3a9172c02a2d6be84ed71cefa95fa5ca50bcfd49b3fb9e1f6e9940f9d21334",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:be583e2c15635b30:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "1f85e44719fc7686eb5826339ea1a2a0b2b8286551f2977082aeffaf56cb7320",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:6e6e71d18e8ab021:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "7e9adf1e120c78d160df9b00808887ecd24178711a3e2bb0d17de44eb0094538",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "used:cc:2f77bd425cc719cf:ab70f90ec14d7f21:967fc3ae76813152",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
      "pid": 4891,
      "sha256": "d53ba55177bfbf4cef00e728305a19e4ca3104206ee5b6223397d56b605a9200",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
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
      "output": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "cargo_pkg_name": "num-traits",
      "cargo_pkg_version": "0.2.19",
      "context_path": "/tmp/native-trace-3361-1783992591488/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-3361-1783992591488/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 4891,
      "ppid": 4839,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
        "/target/debug/build/num-traits-5f67c9ba029d8bfb",
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
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/rustcc0BqLd/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.1vofp9jcxhn009ocqzk4ay33m.1sh2fd1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.73eldb8u6w3wri3t9jp575kzt.1sh2fd1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.770p9yb26gyasntyb9ldmnau1.1sh2fd1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.8qi06urfdqlj5q1w4nm35r5lu.1sh2fd1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.9dh4kivopatvy8qhw6bacl2f3.1sh2fd1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/num-traits-5f67c9ba029d8bfb",
          "kind": "object",
          "path": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build_script_build-5f67c9ba029d8bfb.33gqbe03w0ht7lhmf3b0gilzz.1sh2fd1.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-4891-1783992596014221281.map",
      "pid": 4891,
      "ppid": 4839,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-4891-1783992596014221281.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
      "parsed_event_count": 393,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 394,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.354   ld.lld           5168   5166     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccloKj5q.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-c09a40bfdaa87378/build_script_build-c09a40bfdaa87378 ...\n1.357   rust-lld         5168   5166     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccloKj5q.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.363   collect2         5171   5163     0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.366   ld.lld           5172   5171     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-3d1201f1e2c08588/build_script_build-3d1201f1e2c08588 ...\n1.373   rust-lld         5172   5171     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaRfYDz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.406   build-script-bu  5202   4440     0 /target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build\n1.417   rustc            5207   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.446   rustc            5238   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_de716bda1ec6b2df_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/num-traits-93d6467c1e35fcf1/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.446   rustc            5229   4127     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.475   build-script-bu  5281   4514     0 /target/debug/build/generic-array-eebdc96a43b62923/build-script-build\n1.482   rustc            5282   5281     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n1.491   rustc            5271   5202     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_de716bda1ec6b2df_1 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/num-traits-93d6467c1e35fcf1/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.518   build-script-bu  5334   4693     0 /target/debug/build/quote-c09a40bfdaa87378/build-script-build\n1.529   rustc            5343   4660     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=26a05e840352c101 ...\n1.540   rustc            5365   4440     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name num_traits --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n1.548   rustc            5373   5334     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n1.558   rustc            5374   4938     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=bc175e305027093f ...\n1.558   rustc            5383   5378     0 \n1.558   build-script-bu  5378   4693     0 /target/debug/build/proc-macro2-3d1201f1e2c08588/build-script-build\n1.563   rustc            5386   4594     0 \n1.563   rustc            5387   3810     0 \n1.591   rustc            5413   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span.rs --target powerpc64le-unknown-linux-gnu\n1.605   cc               5430   4912     0 /tmp/native-trace-3564-1783992591752/shims/cc -m64 /target/debug/build/syn-8e197ea489f52d3e/rustcRgej83/symbols.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.0utolxp0p2pr44go2erztto30.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1cvrgnm4obgk14yqlqunqjp4u.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1xzkq3bhi1eo57mr89b2k2gb9.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1ylnp7qbg1r9zjnqcfkjawbvx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.2am004887au5osqtz6ib2utu4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.39pcw8ibwr05y8m8eou11jovl.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3c9zc3un96k1q15lwciixlgr4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3lwtlrtlmwrq3p6hed3ie11bx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3mrl5htmfdamw7o28crx7t481.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4g5m3arf4j3qab9h1d1yo3c8g.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4ih3np50ahfabpkbbfogq3v1w.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4led5rdgn4cyftqptg9usmbti.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4vhof8f02be7dedkn4i39trv3.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.57ooxrgnjzahndwxakbpl0bp2.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5avj5ojvlrxrs6loajwqhmjp1.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5byrf5g503fxkucanzs7j5p9i.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5icz551fby0q1pd8c0nhgfcra.18amxsk.rcgu.o ...\n1.607   cc               5465   5430     0 /usr/bin/cc -m64 /target/debug/build/syn-8e197ea489f52d3e/rustcRgej83/symbols.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.0utolxp0p2pr44go2erztto30.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1cvrgnm4obgk14yqlqunqjp4u.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1xzkq3bhi1eo57mr89b2k2gb9.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.1ylnp7qbg1r9zjnqcfkjawbvx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.2am004887au5osqtz6ib2utu4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.39pcw8ibwr05y8m8eou11jovl.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3c9zc3un96k1q15lwciixlgr4.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3lwtlrtlmwrq3p6hed3ie11bx.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.3mrl5htmfdamw7o28crx7t481.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4g5m3arf4j3qab9h1d1yo3c8g.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4ih3np50ahfabpkbbfogq3v1w.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4led5rdgn4cyftqptg9usmbti.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.4vhof8f02be7dedkn4i39trv3.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.57ooxrgnjzahndwxakbpl0bp2.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5avj5ojvlrxrs6loajwqhmjp1.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5byrf5g503fxkucanzs7j5p9i.18amxsk.rcgu.o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e.5icz551fby0q1pd8c0nhgfcra.18amxsk.rcgu.o ...\n1.617   cc               5474   5374     0 /tmp/native-trace-3651-1783992591802/shims/cc -m64 /target/debug/build/generic-array-eebdc96a43b62923/rustcK5vBGB/symbols.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.33rqti0twnljaal5gi3eqrfkf.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.40ff4s62sl94aqjv6hkvchqir.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.7gtagoq1mqx9dyc96i49liaqs.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9epedn978speey25kflorm7zb.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9gm58v6adhcipgd4b1k8x8unx.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.du5wr0iok2zts0klc6lsqsf1k.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.0nm09f1jy09ysunc6nvd6fw9i.1lhfidy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n1.620   cc               5484   5474     0 /usr/bin/cc -m64 /target/debug/build/generic-array-eebdc96a43b62923/rustcK5vBGB/symbols.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.33rqti0twnljaal5gi3eqrfkf.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.40ff4s62sl94aqjv6hkvchqir.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.7gtagoq1mqx9dyc96i49liaqs.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9epedn978speey25kflorm7zb.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.9gm58v6adhcipgd4b1k8x8unx.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.du5wr0iok2zts0klc6lsqsf1k.1lhfidy.rcgu.o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923.0nm09f1jy09ysunc6nvd6fw9i.1lhfidy.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libversion_check-6524f1f18eb3e9e4.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 ...\n1.627   collect2         5486   5484     0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.627   cc               5489   5482     0 \n1.627   cc               5482   5343     0 /tmp/native-trace-3544-1783992591732/shims/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcxhvl5C/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1t1p6t8.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1t1p6t8.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.627   ld.lld           5490   5486     0 \n1.633   rust-lld         5490   5486     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccIjIq5R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/generic-array-eebdc96a43b62923/build_script_build-eebdc96a43b62923 ...\n1.633   collect2         5492   5489     0 \n1.633   ld.lld           5494   5492     0 \n1.634   rust-lld         5494   5492     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsQpEnh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccsQpEnh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b ...\n1.636   rustc            5483   4004     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.643   collect2         5496   5465     0 \n1.645   ld.lld           5497   5496     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4mFVCq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/syn-8e197ea489f52d3e/build_script_build-8e197ea489f52d3e ...\n1.648   rust-lld         5497   5496     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4mFVCq.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.651   cc               5469   5386     0 /tmp/native-trace-3368-1783992591509/shims/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcMOwZyj/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1wl5rva.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.664   rustc            5518   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_location.rs --target powerpc64le-unknown-linux-gnu\n1.682   cc               5554   5044     0 /tmp/native-trace-3456-1783992591583/shims/cc -m64 /target/debug/build/winapi-78719dd133b3c578/rustcYqMwGs/symbols.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.00ps6htrb975kmbwit7zq3loq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.05op9ji5t4noqkqwgjcyc8zpg.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0lxsobseykngncfa2k11t73hd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0sghx1ve4q9n3mx22tsudkstr.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.16m2820sfqbhi88heaqm6a5yn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.1egcam2my8954zdhbi27q6zxq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.21en0u2i5akvfaz16vbwt8wm2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.24i73zywcmco89bn2f5zo74qw.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2i6mlqmgl4l3o6v6t4wsz3vcd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2td99tt2qqg53jrjmilye4lw2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2tvim9d3kdgg3i84ljbkikptn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2z2ydgxo7y24144vhskejuk7f.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.337dcr78zn3jlr36fpqfnlr4a.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33s8pn2tvxtf1e1ugfilm09z9.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33uuzuyaino25uv0g5s6piu1k.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.3nx8muhgyh0vlnp97exzal8fd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.49tkm7hbt7bct5uz00s6on54s.1nsx7ue.rcgu.o ...\n1.696   cc               5565   5554     0 /usr/bin/cc -m64 /target/debug/build/winapi-78719dd133b3c578/rustcYqMwGs/symbols.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.00ps6htrb975kmbwit7zq3loq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.05op9ji5t4noqkqwgjcyc8zpg.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0lxsobseykngncfa2k11t73hd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.0sghx1ve4q9n3mx22tsudkstr.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.16m2820sfqbhi88heaqm6a5yn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.1egcam2my8954zdhbi27q6zxq.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.21en0u2i5akvfaz16vbwt8wm2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.24i73zywcmco89bn2f5zo74qw.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2i6mlqmgl4l3o6v6t4wsz3vcd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2td99tt2qqg53jrjmilye4lw2.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2tvim9d3kdgg3i84ljbkikptn.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.2z2ydgxo7y24144vhskejuk7f.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.337dcr78zn3jlr36fpqfnlr4a.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33s8pn2tvxtf1e1ugfilm09z9.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.33uuzuyaino25uv0g5s6piu1k.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.3nx8muhgyh0vlnp97exzal8fd.1nsx7ue.rcgu.o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578.49tkm7hbt7bct5uz00s6on54s.1nsx7ue.rcgu.o ...\n1.708   collect2         5569   5565     0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.710   rustc            5568   5378     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --cfg=procmacro2_build_probe --edition=2021 --crate-name=proc_macro2 --crate-type=lib --cap-lints=allow --emit=dep-info,metadata --out-dir /target/powerpc64le-unknown-linux-gnu/debug/build/proc-macro2-3cc4ebcc34b92b16/out/probe src/probe/proc_macro_span_file.rs --target powerpc64le-unknown-linux-gnu\n1.720   cc               5521   5469     0 /usr/bin/cc -m64 /target/debug/build/indexmap-d08c601bd9bf6f9b/rustcMOwZyj/symbols.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.444tokkpsyd5iwa8cxs6pvhur.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.5cuqky9ckgkjmqvqvksse3jwd.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.71oil82l6wcdg2e10ttnfokv1.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.7iut2mk6adk1yam1am1hnw6l6.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.c5p84d2oijlhz7bic0630b8pa.1wl5rva.rcgu.o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b.dwn87bokye4o1jg1xsel408fd.1wl5rva.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-9aa83b36beade1c9.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n1.725   collect2         5574   5521     0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.730   ld.lld           5570   5569     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/winapi-78719dd133b3c578/build_script_build-78719dd133b3c578 ...\n1.730   git              5571   2235138   0 /usr/bin/git blame --root --incremental d3531d3cf8139d4faf98563bb286db3f509aca5c -- native-trace/install_native_trace_tools_static.sh\n1.730   ld.lld           5577   5574     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/indexmap-d08c601bd9bf6f9b/build_script_build-d08c601bd9bf6f9b ...\n1.731   rust-lld         5577   5574     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9LzfOw.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.737   build-script-bu  5579   4660     0 /target/debug/build/indexmap-d08c601bd9bf6f9b/build-script-build\n1.741   rust-lld         5570   5569     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cceW662h.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.741   rustc            5580   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.766   build-script-bu  5602   4938     0 /target/debug/build/generic-array-eebdc96a43b62923/build-script-build\n1.775   rustc            5606   5602     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n1.778   rustc            5603   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_7adc6dbd9212bf83_0 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/indexmap-04414cb891c879d8/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.780   rustc            5605   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n1.823   build-script-bu  5637   4693     0 /target/debug/build/syn-8e197ea489f52d3e/build-script-build\n1.828   rustc            5636   5579     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_7adc6dbd9212bf83_1 --crate-type=lib --out-dir /target/aarch64-unknown-linux-gnu/debug/build/indexmap-04414cb891c879d8/out --emit=llvm-ir --target aarch64-unknown-linux-gnu -\n1.831   rustc            5638   5637     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n1.852   build-script-bu  5650   4594     0 \n1.852   rustc            5646   3810     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.858   rustc            5651   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n1.871   rustc            5654   4660     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=03fb2f105f8b1dc2 ...\n1.881   rustc            5657   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_219ecca48109228b_0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/indexmap-9467ba935f76af73/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.896   rustc            5668   4004     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n1.918   rustc            5679   5650     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name autocfg_219ecca48109228b_1 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/indexmap-9467ba935f76af73/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n1.940   rustc            5683   4514     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=957247ca69051b50 ...\n1.956   rustc            5696   4594     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name indexmap --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arbitrary\", \"quickcheck\", \"rayon\", \"rustc-rayon\", \"serde\", \"serde-1\", \"std\", \"test_debug\", \"test_low_transi -C metadata=0ac8973ac28aad7f ...\n1.994   build-script-bu  5701   4949     0 /target/debug/build/winapi-78719dd133b3c578/build-script-build\n2.012   rustc            5703   4949     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name winapi --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"accctrl\", \"aclapi\", \"activation\", \"adhoc\", \"appmgmt\", \"audioclient\", \"audiosessiontypes\", \"avrt\", \"basetsd\" -C metadata=7d34a9d34ec8fbb2 ...\n2.092   git              5711   2235138   0 /usr/bin/git worktree list --porcelain\n2.111   rustc            5715   4938     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name generic_array --edition=2015 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"more_lengths\", \"serde\", \"zeroize\")) -C metadata=7005c0eb561d969d ...\n2.172   rustc            5723   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n2.338   rustc            5779   4693     0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n3.076   sh               5888   2147557   0 /bin/sh -c which ps\n3.078   which            5888   2147557   0 /usr/bin/which ps\n3.080   sh               5889   2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.082   ps               5889   2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.106   sh               5892   2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.108   cpuUsage.sh      5892   2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 4193774 4193798 4193802 4193840 4193952 4193989 4194042 4194079 4194109 4194137 4194157 4194167 4194173\n3.110   sed              5893   5892     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.112   cat              5894   5892     0 /usr/bin/cat /proc/2240539/stat\n3.114   cat              5895   5892     0 /usr/bin/cat /proc/4193716/stat\n3.115   cat              5896   5892     0 /usr/bin/cat /proc/4193774/stat\n3.117   cat              5897   5892     0 /usr/bin/cat /proc/4193798/stat\n3.118   cat              5900   5892     0 /usr/bin/cat /proc/4193802/stat\n3.120   cat              5901   5892     0 /usr/bin/cat /proc/4193840/stat\n3.121   cat              5902   5892     0 /usr/bin/cat /proc/4193952/stat\n3.123   cat              5903   5892     0 /usr/bin/cat /proc/4193989/stat\n3.124   cat              5904   5892     0 /usr/bin/cat /proc/4194042/stat\n3.126   cat              5905   5892     0 /usr/bin/cat /proc/4194079/stat\n3.127   cat              5906   5892     0 /usr/bin/cat /proc/4194109/stat\n3.129   cat              5907   5892     0 /usr/bin/cat /proc/4194137/stat\n3.130   cat              5908   5892     0 /usr/bin/cat /proc/4194157/stat\n3.131   cat              5909   5892     0 /usr/bin/cat /proc/4194167/stat\n3.133   cat              5910   5892     0 /usr/bin/cat /proc/4194173/stat\n3.134   sleep            5911   5892     0 /usr/bin/sleep 1\n4.137   sed              6401   5892     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.140   cat              6402   5892     0 /usr/bin/cat /proc/2240539/stat\n4.141   cat              6404   5892     0 /usr/bin/cat /proc/4193716/stat\n4.143   cat              6406   5892     0 /usr/bin/cat /proc/4193774/stat\n4.145   cat              6408   5892     0 /usr/bin/cat /proc/4193798/stat\n4.147   cat              6410   5892     0 /usr/bin/cat /proc/4193802/stat\n4.149   cat              6412   5892     0 /usr/bin/cat /proc/4193840/stat\n4.151   cat              6414   5892     0 /usr/bin/cat /proc/4193952/stat\n4.153   cat              6416   5892     0 /usr/bin/cat /proc/4193989/stat\n4.154   cat              6418   5892     0 /usr/bin/cat /proc/4194042/stat\n4.156   cat              6420   5892     0 /usr/bin/cat /proc/4194079/stat\n4.158   cat              6422   5892     0 /usr/bin/cat /proc/4194109/stat\n4.160   cat              6424   5892     0 /usr/bin/cat /proc/4194137/stat\n4.161   cat              6426   5892     0 /usr/bin/cat /proc/4194157/stat\n4.163   cat              6428   5892     0 /usr/bin/cat /proc/4194167/stat\n4.165   cat              6430   5892     0 /usr/bin/cat /proc/4194173/stat\n4.238   runc             6432   4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1973706304 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n4.243   exe              6439   6432     0 /proc/self/exe init\n4.265   curl             6442   6432     0 /usr/bin/curl -f http://localhost:9091/healthz\n8.870   16               6449   1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n8.872   16               6450   1        0 /proc/self/fd/16 --deserialize 138 --log-level info --log-target journal-or-kmsg\n8.886   frpc             6449   1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n8.891   sa1              6450   1        0 /usr/lib64/sa/sa1 1 1\n8.894   sadc             6450   1        0 /usr/lib64/sa/sadc -F -L -S DISK 1 1 /var/log/sa\n10.893  16               6459   1        0 /proc/self/fd/16 --deserialize 155 --log-level info --log-target journal-or-kmsg\n10.897  16               6460   1        0 /proc/self/fd/16 --deserialize 182 --log-level info --log-target journal-or-kmsg\n11.068  systemd-coredum  6459   1        0 /usr/lib/systemd/systemd-coredump\n11.069  drkonqi-coredum  6460   1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 880-6458-0\n11.193  runc             6468   3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process3389782033 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n11.200  exe              6478   6468     0 /proc/self/exe init\n11.227  curl             6480   6468     0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n11.625  9                6487   4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n11.626  abrt-server      6486   1118     0 /usr/bin/abrt-server -s\n11.641  drkonqi-coredum  6487   4003047   0 /usr/libexec/drkonqi-coredump-launcher\n11.657  abrt-handle-eve  6488   6486     0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:30:06.646999-4193631\n11.673  sh               6491   6488     0 /bin/sh -c abrt-action-save-package-data\\n\n11.675  abrt-action-sav  6491   6488     0 /usr/bin/abrt-action-save-package-data\n11.738  sh               6494   6488     0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n11.740  cut              6496   6494     0 /usr/bin/cut -d: -f1\n11.740  cat              6497   6495     0 /usr/bin/cat uid\n11.742  getent           6495   6494     0 /usr/bin/getent passwd 1000\n11.744  lscpu            6498   6494     0 /usr/bin/lscpu\n11.760  sh               6499   6488     0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n11.762  runlevel         6500   6499     0 /usr/bin/runlevel\n11.774  sh               6501   6488     0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n11.776  grep             6502   6501     0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n11.778  grep             6503   6501     0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n11.779  grep             6504   6501     0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n11.781  abrt-action-cor  6505   6501     0 /usr/libexec/abrt-action-coredump -x\n11.849  abrt-action-gen  6506   6501     0 /usr/bin/abrt-action-generate-core-backtrace\n11.907  abrt-action-ana  6507   6501     0 /usr/bin/abrt-action-analyze-vulnerability\n11.909  eu-readelf       6509   6508     0 /usr/bin/eu-readelf -n coredump\n11.910  grep             6510   6508     0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n11.910  sed              6511   6508     0 /usr/bin/sed s/[^0-9]//g\n11.913  gdb              6513   6512     0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n11.930  iconv            6514   6513     0 /usr/bin/iconv -l\n12.039  abrt-action-ana  6523   6501     0 /usr/bin/abrt-action-analyze-c\n12.054  eu-unstrip       6524   6523     0 /usr/bin/eu-unstrip --core=./coredump -n\n12.073  abrt-action-lis  6525   6501     0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n12.143  cat              6527   6526     0 /usr/bin/cat executable\n12.144  cat              6528   6526     0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:30:06.646999-4193631/uid\n12.146  journalctl       6529   6526     0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n12.160  abrt-action-cor  6530   6501     0 /usr/libexec/abrt-action-coredump -r\n12.221  abrt-handle-eve  6531   6486     0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.237  sh               6532   6531     0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n12.239  dbus-send        6532   6531     0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.242  sh               6533   6531     0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n12.243  abrt-action-not  6534   6533     0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n12.314  sh               6535   6534     0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n12.315  reporter-system  6535   6534     0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n17.289  runc             6539   2454     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c --log-format json --systemd-cgroup kill --all a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd 9\n17.311  runc             6546   2454     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c --log-format json --systemd-cgroup delete a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd\n17.477  containerd-shim  6552   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029c delete\n17.480  runc             6558   6552     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04c --log-format json delete --force a5bad21dc65f9b2fa540b7d4f4e9fec4650de7fd0502e291ef89015029cc04cd\n17.516  runc             6564   1148     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 --log-format json --systemd-cgroup kill --all 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17 9\n17.525  runc             6573   1148     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 --log-format json --systemd-cgroup delete 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17\n17.529  sh               6580   6570     0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethb1d16a9\n17.531  ethtool          6581   6580     0 /usr/sbin/ethtool -i vethb1d16a9\n17.531  sed              6582   6580     0 /usr/bin/sed -n s/^driver: //p\n17.539  systemd-sysctl   6585   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb1d16a9 --prefix=/net/ipv4/neigh/vethb1d16a9 --prefix=/net/ipv6/conf/vethb1d16a9 --prefix=/net/ipv6/neigh/vethb1d16a9\n17.719  containerd-shim  6591   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167 delete\n17.722  runc             6598   6591     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb1 --log-format json delete --force 81cd591f5040e7d0e1b43c516145a64fe8234b9c884548d5cbdcffef167dfb17\n17.764  systemd-sysctl   6603   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth706ab07 --prefix=/net/ipv4/neigh/veth706ab07 --prefix=/net/ipv6/conf/veth706ab07 --prefix=/net/ipv6/neigh/veth706ab07\n17.853  runc             6606   775      0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 --log-format json --systemd-cgroup kill --all c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403 9\n17.861  runc             6612   775      0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 --log-format json --systemd-cgroup delete c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403\n18.079  containerd-shim  6618   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f1 delete\n18.083  runc             6625   6618     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f13240 --log-format json delete --force c033f201ebb15a6924c43c025c6cdff9e0724ba4a14e300437dbea540f132403\n18.121  systemd-sysctl   6630   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6de20b5 --prefix=/net/ipv4/neigh/veth6de20b5 --prefix=/net/ipv6/conf/veth6de20b5 --prefix=/net/ipv6/neigh/veth6de20b5\n18.278  sh               6631   2147557   0 /bin/sh -c which ps\n18.279  which            6631   2147557   0 /usr/bin/which ps\n18.282  sh               6632   2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.283  ps               6632   2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n18.314  sh               6633   2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n18.316  cpuUsage.sh      6633   2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716 4193798 4193802 4193840 4193952 4193989 4194042 4194079 4194109 4194137 4194157 4194167 4194173\n18.318  sed              6634   6633     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n18.321  cat              6635   6633     0 /usr/bin/cat /proc/2240539/stat\n18.322  cat              6636   6633     0 /usr/bin/cat /proc/4193716/stat\n18.324  cat              6637   6633     0 /usr/bin/cat /proc/4193798/stat\n18.325  cat              6638   6633     0 /usr/bin/cat /proc/4193802/stat\n18.326  cat              6639   6633     0 /usr/bin/cat /proc/4193840/stat\n18.328  cat              6640   6633     0 /usr/bin/cat /proc/4193952/stat\n18.329  cat              6641   6633     0 /usr/bin/cat /proc/4193989/stat\n18.331  cat              6642   6633     0 /usr/bin/cat /proc/4194042/stat\n18.332  cat              6644   6633     0 /usr/bin/cat /proc/4194079/stat\n18.334  runc             6646   2898     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e --log-format json --systemd-cgroup kill --all 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496 9\n18.334  cat              6645   6633     0 /usr/bin/cat /proc/4194109/stat\n18.335  cat              6647   6633     0 /usr/bin/cat /proc/4194137/stat\n18.337  cat              6653   6633     0 /usr/bin/cat /proc/4194157/stat\n18.338  cat              6654   6633     0 /usr/bin/cat /proc/4194167/stat\n18.340  cat              6655   6633     0 /usr/bin/cat /proc/4194173/stat\n18.341  sleep            6656   6633     0 /usr/bin/sleep 1\n18.344  runc             6657   2898     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e --log-format json --systemd-cgroup delete 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496\n18.512  runc             6663   1313     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d --log-format json --systemd-cgroup kill --all b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a 9\n18.520  runc             6669   1313     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d --log-format json --systemd-cgroup delete b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a\n18.541  containerd-shim  6676   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e delete\n18.544  runc             6683   6676     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e49 --log-format json delete --force 8e51f32e04f5474896b6894fcfd010ca69d30a96ece36982e38a954369e6e496\n18.593  systemd-sysctl   6688   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth97936d7 --prefix=/net/ipv4/neigh/veth97936d7 --prefix=/net/ipv6/conf/veth97936d7 --prefix=/net/ipv6/neigh/veth97936d7\n18.719  containerd-shim  6689   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073d delete\n18.722  runc             6696   6689     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713 --log-format json delete --force b25f1d598855280de9701a873baf1905b589ce5743bab3e0066cc00073da713a\n18.765  systemd-sysctl   6701   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth865c014 --prefix=/net/ipv4/neigh/veth865c014 --prefix=/net/ipv6/conf/veth865c014 --prefix=/net/ipv6/neigh/veth865c014\n19.119  runc             6703   3108     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e --log-format json --systemd-cgroup kill --all 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1 9\n19.127  runc             6709   3108     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e --log-format json --systemd-cgroup delete 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1\n19.326  containerd-shim  6716   1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e delete\n19.329  runc             6722   6716     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c --log-format json delete --force 8496390ecbe6c4bf751f0c354ba69ea0b35452664ac798acc68ebe3fc2e198c1\n19.343  sed              6728   6633     0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n19.346  cat              6729   6633     0 /usr/bin/cat /proc/2240539/stat\n19.348  cat              6731   6633     0 /usr/bin/cat /proc/4193716/stat\n19.350  cat              6733   6633     0 /usr/bin/cat /proc/4193798/stat\n19.353  cat              6736   6633     0 /usr/bin/cat /proc/4193840/stat\n19.355  cat              6738   6633     0 /usr/bin/cat /proc/4193952/stat\n19.357  cat              6741   6633     0 /usr/bin/cat /proc/4194042/stat\n19.359  cat              6743   6633     0 /usr/bin/cat /proc/4194079/stat\n19.361  cat              6745   6633     0 /usr/bin/cat /proc/4194109/stat\n19.363  cat              6747   6633     0 /usr/bin/cat /proc/4194137/stat\n19.364  systemd-sysctl   6748   6570     0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0432ce7 --prefix=/net/ipv4/neigh/veth0432ce7 --prefix=/net/ipv6/conf/veth0432ce7 --prefix=/net/ipv6/neigh/veth0432ce7\n19.365  cat              6750   6633     0 /usr/bin/cat /proc/4194157/stat\n19.368  cat              6752   6633     0 /usr/bin/cat /proc/4194167/stat\n19.369  cat              6754   6633     0 /usr/bin/cat /proc/4194173/stat\n19.379  runc             6756   2967     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bc --log-format json --systemd-cgroup kill --all 71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bce66fb 9\n19.388  runc             6763   2967     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bc --log-format json --systemd-cgroup delete 71ee888fec3646025c3716f1512751786068ee8effee0aaba42944a55bce66fb\n19.398  runc             6769   1762     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b3426 --log-format json --systemd-cgroup kill --all 98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b34269c5fc 9\n19.416  runc             6775   3238     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c30785357 --log-format json --systemd-cgroup kill --all 0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c3078535752656 9\n19.417  runc             6776   1762     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b3426 --log-format json --systemd-cgroup delete 98381f54c3df048736eb7771f22a5d82cd854ddc86cf10baa78ac6b34269c5fc\n19.427  runc             6787   3125     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f --log-format json --systemd-cgroup kill --all 152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f804ad 9\n19.435  runc             6793   3238     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c30785357 --log-format json --systemd-cgroup delete 0fb010b9b2c0bf7d79ef1c85b08b39a85a6528462f626480e4c3078535752656\n19.440  runc             6799   3125     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f --log-format json --systemd-cgroup delete 152d2b73e4a7dc7e81af7bb56c3f1800eecbf0c793a2b56c26f981d302f804ad\n"
    },
    {
      "argv": [
        "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build",
      "pid": 5022,
      "ppid": 4127,
      "root_cargo_pid": 4127,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5023,
      "ppid": 5022,
      "root_cargo_pid": 4127,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_83d94a365f7abd21_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5057,
      "ppid": 5022,
      "root_cargo_pid": 4127,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_83d94a365f7abd21_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5101,
      "ppid": 5022,
      "root_cargo_pid": 4127,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "num-traits",
      "cwd": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "event_id": "bsrun:89e44160041aa890:6cf91e0194f74cbf:d06da07181363fb6",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/num-traits-5f67c9ba029d8bfb/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
      "out_dir": "/target/debug/build/num-traits-5f67c9ba029d8bfb/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
      "success": true,
      "target": null,
      "version": "0.2.19",
      "_owner": {
        "crate": "num-traits",
        "version": "0.2.19",
        "package_id": "path+file:///tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19#num-traits@0.2.19",
        "manifest_dir": "/tmp/crate-build-ppc64le-n998kdmc/src/num-traits-0.2.19",
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
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5023,
      "ppid": 5022,
      "root_cargo_pid": 4127,
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
        "autocfg_83d94a365f7abd21_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5057,
      "ppid": 5022,
      "root_cargo_pid": 4127,
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
        "autocfg_83d94a365f7abd21_1",
        "--crate-type=lib",
        "--out-dir",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/num-traits-1c86c29199d3c47f/out",
        "--emit=llvm-ir",
        "--target",
        "powerpc64le-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 5022,
      "build_script_target_dir": "num-traits-5f67c9ba029d8bfb",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 5101,
      "ppid": 5022,
      "root_cargo_pid": 4127,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 19,
    "crate": "num-traits",
    "version": "0.2.19",
    "crate_id": "4746",
    "version_id": "1134283",
    "downloads": 342127226,
    "cumulative_downloads": 7779414351,
    "cumulative_share_of_global": 0.029085434335347448,
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
