# `esaxx-rs` `0.1.10`

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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
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
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
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
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1250187-1784008273032424346.map",
  "pid": 1250187,
  "ppid": 1250173,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1250187-1784008273032424346.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a`

Owner: `esaxx-rs` `0.1.10`

### Source files

* `/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/src/esaxx.cpp`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-mcmodel=medany",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
    "-c",
    "src/esaxx.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-g++",
  "pid": 1250210,
  "ppid": 1250208,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/",
    "-dumpbase",
    "esaxx.cpp",
    "-dumpbase-ext",
    ".cpp",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-mcmodel=medany",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1250211,
  "ppid": 1250210,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1250093,
  "build_script_root_pid": 1250208,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

### Archive records

#### Record 1

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1250213,
  "ppid": 1250208,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1250093,
  "build_script_root_pid": 1250208,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
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
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
      "name": "aho-corasick",
      "version": "1.1.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
      "name": "anes",
      "version": "0.1.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
      "name": "anstyle",
      "version": "1.0.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
      "name": "autocfg",
      "version": "1.1.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
      "name": "bitflags",
      "version": "2.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
      "name": "bumpalo",
      "version": "3.14.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
      "name": "cast",
      "version": "0.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
      "name": "cc",
      "version": "1.0.83",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
      "name": "ciborium",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
      "name": "ciborium-io",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
      "name": "ciborium-ll",
      "version": "0.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
      "name": "clap",
      "version": "4.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
      "name": "clap_builder",
      "version": "4.4.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
      "name": "clap_lex",
      "version": "0.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
      "name": "criterion",
      "version": "0.5.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
      "name": "criterion-plot",
      "version": "0.5.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
      "name": "crossbeam-deque",
      "version": "0.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
      "name": "crossbeam-epoch",
      "version": "0.9.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
      "name": "crossbeam-utils",
      "version": "0.8.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
      "name": "either",
      "version": "1.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
      "name": "errno",
      "version": "0.3.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
      "name": "errno-dragonfly",
      "version": "0.1.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "name": "esaxx-rs",
      "version": "0.1.10",
      "manifest_path": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
      "name": "half",
      "version": "1.8.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
      "name": "hermit-abi",
      "version": "0.3.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
      "name": "is-terminal",
      "version": "0.4.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
      "name": "itertools",
      "version": "0.10.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
      "name": "itoa",
      "version": "1.0.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
      "name": "js-sys",
      "version": "0.3.64",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
      "name": "libc",
      "version": "0.2.148",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
      "name": "linux-raw-sys",
      "version": "0.4.8",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
      "name": "log",
      "version": "0.4.20",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
      "name": "memchr",
      "version": "2.6.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
      "name": "memoffset",
      "version": "0.9.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
      "name": "num-traits",
      "version": "0.2.16",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
      "name": "once_cell",
      "version": "1.18.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
      "name": "oorandom",
      "version": "11.1.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
      "name": "plotters",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
      "name": "plotters-backend",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
      "name": "plotters-svg",
      "version": "0.3.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
      "name": "proc-macro2",
      "version": "1.0.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
      "name": "quote",
      "version": "1.0.33",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
      "name": "rayon",
      "version": "1.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
      "name": "rayon-core",
      "version": "1.12.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
      "name": "regex",
      "version": "1.9.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
      "name": "regex-automata",
      "version": "0.3.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
      "name": "regex-syntax",
      "version": "0.7.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
      "name": "rustix",
      "version": "0.38.17",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
      "name": "ryu",
      "version": "1.0.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
      "name": "same-file",
      "version": "1.0.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
      "name": "scopeguard",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
      "name": "serde",
      "version": "1.0.188",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
      "name": "serde_derive",
      "version": "1.0.188",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
      "name": "serde_json",
      "version": "1.0.107",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
      "name": "syn",
      "version": "2.0.37",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
      "name": "tinytemplate",
      "version": "1.2.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
      "name": "unicode-ident",
      "version": "1.0.12",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
      "name": "walkdir",
      "version": "2.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
      "name": "wasm-bindgen",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
      "name": "wasm-bindgen-backend",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
      "name": "wasm-bindgen-macro",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
      "name": "wasm-bindgen-macro-support",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
      "name": "wasm-bindgen-shared",
      "version": "0.2.87",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
      "name": "web-sys",
      "version": "0.3.64",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
      "name": "winapi-util",
      "version": "0.1.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
      "name": "winapi-x86_64-pc-windows-gnu",
      "version": "0.4.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
      "name": "windows-sys",
      "version": "0.48.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
      "name": "windows-targets",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
      "name": "windows_aarch64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
      "name": "windows_aarch64_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
      "name": "windows_i686_gnu",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
      "name": "windows_i686_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
      "name": "windows_x86_64_gnu",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
      "name": "windows_x86_64_gnullvm",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
      "name": "windows_x86_64_msvc",
      "version": "0.48.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5"
    }
  ],
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1250108,
  "ppid": 1250100,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:979d3783324e8fe1:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
  "pid": 1250108,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:ffbb52dee619e4f7:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
  "pid": 1250108,
  "sha256": "0084afdb6795e37eed7874e70d007107abbf84e8be21d962ee5ecd567f7f3a7d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:6cd16efd838c1c1f:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
  "pid": 1250108,
  "sha256": "42de4168bfa675af3241b604230d4f16a1a324228feaa59aab5a71ca5f3153b5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "used:cc:018871c2723b82d0:a759f47395afa91f:3e55491827d9b9d7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
  "pid": 1250108,
  "sha256": "e4901fc88fe2f91f7fad9706b9a4cdff37a573f9a087101074a5b4e6e11154c0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
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
  "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.148",
  "context_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1250108,
  "ppid": 1250100,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k",
    "/target/debug/build/libc-8a12625678126bc3",
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
      "directory": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-8a12625678126bc3",
      "kind": "object",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1250108-1784008272086342782.map",
  "pid": 1250108,
  "ppid": 1250100,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1250108-1784008272086342782.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1250187,
  "ppid": 1250173,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:eabd8c057b236cb0:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
  "pid": 1250187,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:8d1e48c00eb0e0d1:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "6bb2f27ebae77e49347411e1122f77edc4cf710cdfef7ca76b9088637c9ef864",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:fb56f5da5b8c8d34:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "959c985224b886e8e7a8ff8537420387038d321448e1819013713d98bcc8cdd6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:9a0cb788061ae126:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "968e2eb08fc82414a0e296071829ca46b0e25d65014f7c79319afb4d7f6cc447",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:1c4ae62129cfd0e1:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "7421d0c973c066d02fd93a93bfa62129d26bd71fb58e65f7460f4c960750d61a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:437274696d42537c:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "ee8e2845fc3fe74bda4d9035f21ff93d6780b5820ccd8a536647cb3eb5885bdc",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:a4d4c65ae1de90d3:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "51def7cb68b197ea9156528d029d0f5c410a3723128c1664e8e8429169ba3618",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:f70783603c9af50d:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "3adfe7a5133614cf27e44928fbc7fa12ab1d0eebfe9f4d8f13dea4a1b0750130",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:bfd0874ba2f0e3f1:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "26c300965897a5b69b9ccca398c1d746548c3744a328d2a471df168a1026e37a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "used:cc:70690ae10143e16b:2b3b51976d75b98e:90bdbcf437dbe434",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
  "pid": 1250187,
  "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
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
  "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "cargo_pkg_name": "esaxx-rs",
  "cargo_pkg_version": "0.1.10",
  "context_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1250187,
  "ppid": 1250173,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
    "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
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
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
      "kind": "object",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.1.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1250187-1784008273032424346.map",
  "pid": 1250187,
  "ppid": 1250173,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1250187-1784008273032424346.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cargo_manifest_dir"
  }
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

#### Record 25

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 46,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 47,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.088   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1250093 1250073   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.099   rustc            1250094 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.131   rustc            1250100 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.234   cc               1250108 1250100   0 /tmp/native-trace-1250073-1784008269808/shims/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.235   cc               1250109 1250108   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.237   collect2         1250110 1250109   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.238   ld.lld           1250111 1250110   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n0.239   rust-lld         1250111 1250110   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.277   build-script-bu  1250129 1250093   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n0.278   rustc            1250130 1250129   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n0.289   rustc            1250135 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.548   16               1250139 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n0.565   frpc             1250139 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n0.752   rustc            1250148 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n1.147   rustc            1250173 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n1.181   cc               1250187 1250173   0 /tmp/native-trace-1250073-1784008269808/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.181   cc               1250188 1250187   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.184   collect2         1250189 1250188   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.185   ld.lld           1250190 1250189   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n1.186   rust-lld         1250190 1250189   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.236   build-script-bu  1250208 1250093   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n1.237   riscv64-linux-g  1250210 1250208   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -I src -Wall -Wextra -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o -c src/esaxx.cpp\n1.239   cc1plus          1250211 1250210   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/ -dumpbase esaxx.cpp -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -mcmodel=medany ...\n1.491   as               1250212 1250210   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o /tmp/ccBFTQt8.s\n1.507   riscv64-linux-g  1250213 1250208   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o\n1.523   riscv64-linux-g  1250214 1250208   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a\n1.541   rustc            1250216 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n2.611   runc             1250264 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2565639964 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n2.615   exe              1250272 1250264   0 /proc/self/exe init\n2.635   curl             1250274 1250264   0 /usr/bin/curl -f http://localhost:9091/healthz\n3.034   sh               1250281 2147557   0 /bin/sh -c which ps\n3.035   which            1250281 2147557   0 /usr/bin/which ps\n3.038   sh               1250282 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.039   ps               1250282 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.066   sh               1250283 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.067   cpuUsage.sh      1250283 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n3.069   sed              1250284 1250283   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.072   cat              1250285 1250283   0 /usr/bin/cat /proc/2240539/stat\n3.073   sleep            1250286 1250283   0 /usr/bin/sleep 1\n4.075   sed              1250287 1250283   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.078   cat              1250288 1250283   0 /usr/bin/cat /proc/2240539/stat\n13.530  runc             1250292 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process302736395 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n13.537  exe              1250299 1250292   0 /proc/self/exe init\n13.570  curl             1250301 1250292   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.798  16               1250308 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n15.813  frpc             1250308 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n"
}
```

#### Record 26

```json
{
  "argv": [
    "/target/debug/build/libc-8a12625678126bc3/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250129,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
  "pid": 1250129,
  "ppid": 1250093,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_out_dir": "/target/debug/build/libc-8a12625678126bc3/out"
}
```

#### Record 27

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250129,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1250130,
  "ppid": 1250129,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_build_script_out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "pid": 1250208,
  "ppid": 1250093,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-mcmodel=medany",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-std=c++11",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
    "-c",
    "src/esaxx.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-g++",
  "pid": 1250210,
  "ppid": 1250208,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/",
    "-dumpbase",
    "esaxx.cpp",
    "-dumpbase-ext",
    ".cpp",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-mcmodel=medany",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
  "pid": 1250211,
  "ppid": 1250210,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "-I",
    "src",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
    "/tmp/ccBFTQt8.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 1250212,
  "ppid": 1250210,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 1250213,
  "ppid": 1250208,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "s",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250208,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 1250214,
  "ppid": 1250208,
  "root_cargo_pid": 1250093,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "event_id": "bsrun:2ebdc03c5a2acb3f:d2cbd9eb7f36ae5e:094a542f6f4ffc0f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
  "out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
  "success": true,
  "target": null,
  "version": "0.2.148",
  "_owner": {
    "crate": "libc",
    "version": "0.2.148",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
    "source": "cwd_prefix"
  }
}
```

#### Record 35

```json
{
  "crate": "esaxx-rs",
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "event_id": "bsrun:5f15689fd3e06e1e:58c8166d76a53504:5698292d0e3f3d21",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
  "success": true,
  "target": null,
  "version": "0.1.10",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1250129,
  "build_script_target_dir": "libc-8a12625678126bc3",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 1250130,
  "ppid": 1250129,
  "root_cargo_pid": 1250093,
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
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "-D_GNU_SOURCE",
    "src/esaxx.cpp",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/",
    "-dumpbase",
    "esaxx.cpp",
    "-dumpbase-ext",
    ".cpp",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-mcmodel=medany",
    "..."
  ],
  "src": "src/esaxx.cpp",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 1250211,
  "ppid": 1250210,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1250093,
  "build_script_root_pid": 1250208,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cq",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 1250213,
  "ppid": 1250208,
  "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "root_cargo_pid": 1250093,
  "build_script_root_pid": 1250208,
  "build_script_related": true,
  "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
  "_owner": {
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
    "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
  "_build_script_out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T05:51:30.838975+00:00",
  "crate": "esaxx-rs",
  "version": "0.1.10",
  "architecture": "riscv64",
  "duration_seconds": 21.615232328884304,
  "trace_record_count": 35,
  "trace_owner_summary": {
    "owner_package_count": 78,
    "owner_packages": [
      {
        "crate": "winapi-x86_64-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro-support",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml"
      },
      {
        "crate": "winapi-i686-pc-windows-gnu",
        "version": "0.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-i686-pc-windows-gnu@0.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-i686-pc-windows-gnu-0.4.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-backend",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-shared",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen-macro",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml"
      },
      {
        "crate": "crossbeam-epoch",
        "version": "0.9.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml"
      },
      {
        "crate": "crossbeam-utils",
        "version": "0.8.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml"
      },
      {
        "crate": "plotters-backend",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.48.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml"
      },
      {
        "crate": "crossbeam-deque",
        "version": "0.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml"
      },
      {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml"
      },
      {
        "crate": "criterion-plot",
        "version": "0.5.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.188",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.12",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml"
      },
      {
        "crate": "linux-raw-sys",
        "version": "0.4.8",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml"
      },
      {
        "crate": "wasm-bindgen",
        "version": "0.2.87",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml"
      },
      {
        "crate": "clap_builder",
        "version": "4.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml"
      },
      {
        "crate": "plotters-svg",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.67",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.7.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.107",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml"
      },
      {
        "crate": "tinytemplate",
        "version": "1.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.48.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml"
      },
      {
        "crate": "ciborium-io",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml"
      },
      {
        "crate": "ciborium-ll",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml"
      },
      {
        "crate": "is-terminal",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml"
      },
      {
        "crate": "num-traits",
        "version": "0.2.16",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml"
      },
      {
        "crate": "rayon-core",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml"
      },
      {
        "crate": "winapi-util",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml"
      },
      {
        "crate": "hermit-abi",
        "version": "0.3.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml"
      },
      {
        "crate": "itertools",
        "version": "0.10.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.18.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml"
      },
      {
        "crate": "scopeguard",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml"
      },
      {
        "crate": "criterion",
        "version": "0.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml"
      },
      {
        "crate": "oorandom",
        "version": "11.1.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml"
      },
      {
        "crate": "same-file",
        "version": "1.0.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml"
      },
      {
        "crate": "bumpalo",
        "version": "3.14.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml"
      },
      {
        "crate": "ciborium",
        "version": "0.2.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml"
      },
      {
        "crate": "clap_lex",
        "version": "0.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml"
      },
      {
        "crate": "plotters",
        "version": "0.3.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml"
      },
      {
        "crate": "rustix",
        "version": "0.38.17",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml"
      },
      {
        "crate": "web-sys",
        "version": "0.3.64",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml"
      },
      {
        "crate": "anstyle",
        "version": "1.0.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml"
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
        "version": "0.3.64",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.188",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml"
      },
      {
        "crate": "walkdir",
        "version": "2.4.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml"
      },
      {
        "crate": "cfg-if",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml"
      },
      {
        "crate": "either",
        "version": "1.9.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.6.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml"
      },
      {
        "crate": "winapi",
        "version": "0.3.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi@0.3.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-0.3.9/Cargo.toml"
      },
      {
        "crate": "errno",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml"
      },
      {
        "crate": "rayon",
        "version": "1.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.9.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml"
      },
      {
        "crate": "anes",
        "version": "0.1.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml"
      },
      {
        "crate": "cast",
        "version": "0.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml"
      },
      {
        "crate": "clap",
        "version": "4.4.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml"
      },
      {
        "crate": "half",
        "version": "1.8.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml"
      },
      {
        "crate": "log",
        "version": "0.4.20",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml"
      },
      {
        "crate": "ryu",
        "version": "1.0.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.37",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.0.83",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml"
      },
      {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "manifest_path": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/Cargo.toml"
      }
    ],
    "attributed_event_count": 25,
    "unattributed_event_count": 10,
    "owners": [
      {
        "crate": "esaxx-rs",
        "version": "0.1.10",
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
        "crate": "libc",
        "version": "0.2.148",
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
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.1",
          "name": "aho-corasick",
          "version": "1.1.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anes@0.1.6",
          "name": "anes",
          "version": "0.1.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anes-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#anstyle@1.0.4",
          "name": "anstyle",
          "version": "1.0.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/anstyle-1.0.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.1.0",
          "name": "autocfg",
          "version": "1.1.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.1.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.4.0",
          "name": "bitflags",
          "version": "2.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bumpalo@3.14.0",
          "name": "bumpalo",
          "version": "3.14.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bumpalo-3.14.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cast@0.3.0",
          "name": "cast",
          "version": "0.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cast-0.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.0.83",
          "name": "cc",
          "version": "1.0.83",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium@0.2.1",
          "name": "ciborium",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-io@0.2.1",
          "name": "ciborium-io",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-io-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ciborium-ll@0.2.1",
          "name": "ciborium-ll",
          "version": "0.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ciborium-ll-0.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap@4.4.6",
          "name": "clap",
          "version": "4.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap-4.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_builder@4.4.6",
          "name": "clap_builder",
          "version": "4.4.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_builder-4.4.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#clap_lex@0.5.1",
          "name": "clap_lex",
          "version": "0.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/clap_lex-0.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion@0.5.1",
          "name": "criterion",
          "version": "0.5.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-0.5.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#criterion-plot@0.5.0",
          "name": "criterion-plot",
          "version": "0.5.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/criterion-plot-0.5.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-deque@0.8.3",
          "name": "crossbeam-deque",
          "version": "0.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-epoch@0.9.15",
          "name": "crossbeam-epoch",
          "version": "0.9.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#crossbeam-utils@0.8.16",
          "name": "crossbeam-utils",
          "version": "0.8.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#either@1.9.0",
          "name": "either",
          "version": "1.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/either-1.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno@0.3.4",
          "name": "errno",
          "version": "0.3.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-0.3.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#errno-dragonfly@0.1.2",
          "name": "errno-dragonfly",
          "version": "0.1.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/errno-dragonfly-0.1.2"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
          "name": "esaxx-rs",
          "version": "0.1.10",
          "manifest_path": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#half@1.8.2",
          "name": "half",
          "version": "1.8.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/half-1.8.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#hermit-abi@0.3.3",
          "name": "hermit-abi",
          "version": "0.3.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hermit-abi-0.3.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#is-terminal@0.4.9",
          "name": "is-terminal",
          "version": "0.4.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/is-terminal-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itertools@0.10.5",
          "name": "itertools",
          "version": "0.10.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itertools-0.10.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.9",
          "name": "itoa",
          "version": "1.0.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#js-sys@0.3.64",
          "name": "js-sys",
          "version": "0.3.64",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/js-sys-0.3.64"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
          "name": "libc",
          "version": "0.2.148",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.4.8",
          "name": "linux-raw-sys",
          "version": "0.4.8",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.4.8"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#log@0.4.20",
          "name": "log",
          "version": "0.4.20",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/log-0.4.20"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.6.4",
          "name": "memchr",
          "version": "2.6.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.6.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memoffset@0.9.0",
          "name": "memoffset",
          "version": "0.9.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memoffset-0.9.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#num-traits@0.2.16",
          "name": "num-traits",
          "version": "0.2.16",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/num-traits-0.2.16"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.18.0",
          "name": "once_cell",
          "version": "1.18.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.18.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#oorandom@11.1.3",
          "name": "oorandom",
          "version": "11.1.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/oorandom-11.1.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters@0.3.5",
          "name": "plotters",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-backend@0.3.5",
          "name": "plotters-backend",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-backend-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#plotters-svg@0.3.5",
          "name": "plotters-svg",
          "version": "0.3.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/plotters-svg-0.3.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.67",
          "name": "proc-macro2",
          "version": "1.0.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.67"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.33",
          "name": "quote",
          "version": "1.0.33",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.33"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon@1.8.0",
          "name": "rayon",
          "version": "1.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-1.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rayon-core@1.12.0",
          "name": "rayon-core",
          "version": "1.12.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rayon-core-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.9.6",
          "name": "regex",
          "version": "1.9.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.9.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.3.9",
          "name": "regex-automata",
          "version": "0.3.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.3.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.7.5",
          "name": "regex-syntax",
          "version": "0.7.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.7.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustix@0.38.17",
          "name": "rustix",
          "version": "0.38.17",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustix-0.38.17"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#ryu@1.0.15",
          "name": "ryu",
          "version": "1.0.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ryu-1.0.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#same-file@1.0.6",
          "name": "same-file",
          "version": "1.0.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/same-file-1.0.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#scopeguard@1.2.0",
          "name": "scopeguard",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/scopeguard-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.188",
          "name": "serde",
          "version": "1.0.188",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.188"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.188",
          "name": "serde_derive",
          "version": "1.0.188",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.188"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.107",
          "name": "serde_json",
          "version": "1.0.107",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.107"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.37",
          "name": "syn",
          "version": "2.0.37",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.37"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tinytemplate@1.2.1",
          "name": "tinytemplate",
          "version": "1.2.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tinytemplate-1.2.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.12",
          "name": "unicode-ident",
          "version": "1.0.12",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.12"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#walkdir@2.4.0",
          "name": "walkdir",
          "version": "2.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/walkdir-2.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen@0.2.87",
          "name": "wasm-bindgen",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-backend@0.2.87",
          "name": "wasm-bindgen-backend",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-backend-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro@0.2.87",
          "name": "wasm-bindgen-macro",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-macro-support@0.2.87",
          "name": "wasm-bindgen-macro-support",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-macro-support-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#wasm-bindgen-shared@0.2.87",
          "name": "wasm-bindgen-shared",
          "version": "0.2.87",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/wasm-bindgen-shared-0.2.87"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#web-sys@0.3.64",
          "name": "web-sys",
          "version": "0.3.64",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/web-sys-0.3.64"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-util@0.1.6",
          "name": "winapi-util",
          "version": "0.1.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-util-0.1.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#winapi-x86_64-pc-windows-gnu@0.4.0",
          "name": "winapi-x86_64-pc-windows-gnu",
          "version": "0.4.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/winapi-x86_64-pc-windows-gnu-0.4.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.48.0",
          "name": "windows-sys",
          "version": "0.48.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.48.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.48.5",
          "name": "windows-targets",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.48.5",
          "name": "windows_aarch64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.48.5",
          "name": "windows_aarch64_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.48.5",
          "name": "windows_i686_gnu",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.48.5",
          "name": "windows_i686_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.48.5",
          "name": "windows_x86_64_gnu",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.48.5",
          "name": "windows_x86_64_gnullvm",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.48.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.48.5",
          "name": "windows_x86_64_msvc",
          "version": "0.48.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.48.5"
        }
      ],
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1250108,
      "ppid": 1250100,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:979d3783324e8fe1:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
      "pid": 1250108,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:ffbb52dee619e4f7:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
      "pid": 1250108,
      "sha256": "0084afdb6795e37eed7874e70d007107abbf84e8be21d962ee5ecd567f7f3a7d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:6cd16efd838c1c1f:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
      "pid": 1250108,
      "sha256": "42de4168bfa675af3241b604230d4f16a1a324228feaa59aab5a71ca5f3153b5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "used:cc:018871c2723b82d0:a759f47395afa91f:3e55491827d9b9d7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
      "pid": 1250108,
      "sha256": "e4901fc88fe2f91f7fad9706b9a4cdff37a573f9a087101074a5b4e6e11154c0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
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
      "output": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.148",
      "context_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1250108,
      "ppid": 1250100,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k",
        "/target/debug/build/libc-8a12625678126bc3",
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
          "directory": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-8a12625678126bc3",
          "kind": "object",
          "path": "/target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1250108-1784008272086342782.map",
      "pid": 1250108,
      "ppid": 1250100,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1250108-1784008272086342782.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1250187,
      "ppid": 1250173,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:eabd8c057b236cb0:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
      "pid": 1250187,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:8d1e48c00eb0e0d1:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "6bb2f27ebae77e49347411e1122f77edc4cf710cdfef7ca76b9088637c9ef864",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:fb56f5da5b8c8d34:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "959c985224b886e8e7a8ff8537420387038d321448e1819013713d98bcc8cdd6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:9a0cb788061ae126:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "968e2eb08fc82414a0e296071829ca46b0e25d65014f7c79319afb4d7f6cc447",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:1c4ae62129cfd0e1:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "7421d0c973c066d02fd93a93bfa62129d26bd71fb58e65f7460f4c960750d61a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:437274696d42537c:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "ee8e2845fc3fe74bda4d9035f21ff93d6780b5820ccd8a536647cb3eb5885bdc",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:a4d4c65ae1de90d3:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "51def7cb68b197ea9156528d029d0f5c410a3723128c1664e8e8429169ba3618",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:f70783603c9af50d:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "3adfe7a5133614cf27e44928fbc7fa12ab1d0eebfe9f4d8f13dea4a1b0750130",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:bfd0874ba2f0e3f1:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "26c300965897a5b69b9ccca398c1d746548c3744a328d2a471df168a1026e37a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "used:cc:70690ae10143e16b:2b3b51976d75b98e:90bdbcf437dbe434",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
      "pid": 1250187,
      "sha256": "b5d70f58226e48020baead62f879a65339ae344afe36358deccd208d1c4137a6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
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
      "output": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "cargo_pkg_name": "esaxx-rs",
      "cargo_pkg_version": "0.1.10",
      "context_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1250073-1784008269808/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1250187,
      "ppid": 1250173,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib",
        "/target/debug/deps/liblibc-a67fd4811337956e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
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
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c",
          "kind": "object",
          "path": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib(cc-7b7dcb2d48cfd1e3.cc.b64de45bcccc2e22-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/liblibc-a67fd4811337956e.rlib(libc-a67fd4811337956e.libc.1747362be0f7f6e5-cgu.1.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1250187-1784008273032424346.map",
      "pid": 1250187,
      "ppid": 1250173,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1250187-1784008273032424346.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
      "parsed_event_count": 46,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 47,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.088   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            1250093 1250073   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.099   rustc            1250094 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.131   rustc            1250100 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.234   cc               1250108 1250100   0 /tmp/native-trace-1250073-1784008269808/shims/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.235   cc               1250109 1250108   0 /usr/bin/cc -m64 /target/debug/build/libc-8a12625678126bc3/rustcz3lI2k/symbols.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.0.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.build_script_build.3d3436de814ab24-cgu.1.rcgu.o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3.blu6pmgpstjvg9vsaaorbwvcq.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n0.237   collect2         1250110 1250109   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.238   ld.lld           1250111 1250110   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a12625678126bc3/build_script_build-8a12625678126bc3 ...\n0.239   rust-lld         1250111 1250110   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc7eoPhV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.277   build-script-bu  1250129 1250093   0 /target/debug/build/libc-8a12625678126bc3/build-script-build\n0.278   rustc            1250130 1250129   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n0.289   rustc            1250135 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"extra_traits\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n0.548   16               1250139 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n0.565   frpc             1250139 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n0.752   rustc            1250148 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.0.83/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"jobserver\", \"parallel\")) -C metadata=18831150b9e7f196 ...\n1.147   rustc            1250173 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n1.181   cc               1250187 1250173   0 /tmp/native-trace-1250073-1784008269808/shims/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.181   cc               1250188 1250187   0 /usr/bin/cc -m64 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/rustc5ci01i/symbols.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.02kgpp3qv4vmnhjkcndmrg65t.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6df7n33eiu5q713krvduxd81e.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.7mi0mifrk3dwoq0hacip9108g.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.9anr6nhqc34ly7rc6tm637osb.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.ang15l1wv33mxa0p1xq29eb1d.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.at3my4f4qt5remso7wkt2nqb8.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.axjd7mq61guuuj06fsrthjvtw.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.chiqys8d55ybez19kdtqygns3.1nbd1a1.rcgu.o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c.6dyemy25zkuwidsvpxs8c2r0f.1nbd1a1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7b7dcb2d48cfd1e3.rlib /target/debug/deps/liblibc-a67fd4811337956e.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 ...\n1.184   collect2         1250189 1250188   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n1.185   ld.lld           1250190 1250189   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build_script_build-9992bbfc27a34b5c ...\n1.186   rust-lld         1250190 1250189   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0rN6Y9.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n1.236   build-script-bu  1250208 1250093   0 /target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build\n1.237   riscv64-linux-g  1250210 1250208   0 /usr/bin/riscv64-linux-gnu-g++ -O0 -ffunction-sections -fdata-sections -fPIC -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -mcmodel=medany -I src -Wall -Wextra -std=c++11 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o -c src/esaxx.cpp\n1.239   cc1plus          1250211 1250210   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu -D_GNU_SOURCE src/esaxx.cpp -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/ -dumpbase esaxx.cpp -dumpbase-ext .cpp -march=rv64gc -mabi=lp64d -mcmodel=medany ...\n1.491   as               1250212 1250210   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o /tmp/ccBFTQt8.s\n1.507   riscv64-linux-g  1250213 1250208   0 /usr/bin/riscv64-linux-gnu-ar cq /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o\n1.523   riscv64-linux-g  1250214 1250208   0 /usr/bin/riscv64-linux-gnu-ar s /target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a\n1.541   rustc            1250216 1250093   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name esaxx_rs --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"cc\" --cfg feature=\"cpp\" --cfg feature=\"default\" ...\n2.611   runc             1250264 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process2565639964 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n2.615   exe              1250272 1250264   0 /proc/self/exe init\n2.635   curl             1250274 1250264   0 /usr/bin/curl -f http://localhost:9091/healthz\n3.034   sh               1250281 2147557   0 /bin/sh -c which ps\n3.035   which            1250281 2147557   0 /usr/bin/which ps\n3.038   sh               1250282 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.039   ps               1250282 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n3.066   sh               1250283 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n3.067   cpuUsage.sh      1250283 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539\n3.069   sed              1250284 1250283   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n3.072   cat              1250285 1250283   0 /usr/bin/cat /proc/2240539/stat\n3.073   sleep            1250286 1250283   0 /usr/bin/sleep 1\n4.075   sed              1250287 1250283   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n4.078   cat              1250288 1250283   0 /usr/bin/cat /proc/2240539/stat\n13.530  runc             1250292 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process302736395 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n13.537  exe              1250299 1250292   0 /proc/self/exe init\n13.570  curl             1250301 1250292   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n15.798  16               1250308 1        0 /proc/self/fd/16 --deserialize 127 --log-level info --log-target journal-or-kmsg\n15.813  frpc             1250308 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-8a12625678126bc3/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250129,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
      "pid": 1250129,
      "ppid": 1250093,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250129,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1250130,
      "ppid": 1250129,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "pid": 1250208,
      "ppid": 1250093,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-mcmodel=medany",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-std=c++11",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
        "-c",
        "src/esaxx.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-g++",
      "pid": 1250210,
      "ppid": 1250208,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
        "-quiet",
        "-I",
        "src",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "-D_GNU_SOURCE",
        "src/esaxx.cpp",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/",
        "-dumpbase",
        "esaxx.cpp",
        "-dumpbase-ext",
        ".cpp",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-mcmodel=medany",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1plus",
      "pid": 1250211,
      "ppid": 1250210,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "-I",
        "src",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o",
        "/tmp/ccBFTQt8.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 1250212,
      "ppid": 1250210,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cq",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/src/esaxx.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 1250213,
      "ppid": 1250208,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "s",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/esaxx-rs-908d5e9cd5a4a2e9/out/libesaxx.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1250208,
      "build_script_target_dir": "esaxx-rs-9992bbfc27a34b5c",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 1250214,
      "ppid": 1250208,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "event_id": "bsrun:2ebdc03c5a2acb3f:d2cbd9eb7f36ae5e:094a542f6f4ffc0f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-8a12625678126bc3/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
      "out_dir": "/target/debug/build/libc-8a12625678126bc3/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
      "success": true,
      "target": null,
      "version": "0.2.148",
      "_owner": {
        "crate": "libc",
        "version": "0.2.148",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.148",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.148",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "esaxx-rs",
      "cwd": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "event_id": "bsrun:5f15689fd3e06e1e:58c8166d76a53504:5698292d0e3f3d21",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
      "out_dir": "/target/debug/build/esaxx-rs-9992bbfc27a34b5c/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
      "success": true,
      "target": null,
      "version": "0.1.10",
      "_owner": {
        "crate": "esaxx-rs",
        "version": "0.1.10",
        "package_id": "path+file:///tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10#esaxx-rs@0.1.10",
        "manifest_dir": "/tmp/crate-build-riscv64-1ry42oak/src/esaxx-rs-0.1.10",
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
      "build_script_root_pid": 1250129,
      "build_script_target_dir": "libc-8a12625678126bc3",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 1250130,
      "ppid": 1250129,
      "root_cargo_pid": 1250093,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 1361,
    "crate": "esaxx-rs",
    "version": "0.1.10",
    "crate_id": "250592",
    "version_id": "916920",
    "downloads": 13464958,
    "cumulative_downloads": 95446591387,
    "cumulative_share_of_global": 0.3568527707953331,
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
