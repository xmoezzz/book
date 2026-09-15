# `tree-sitter-python` `0.23.6`

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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
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
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-901423-1783998225926571325.map",
  "pid": 901423,
  "ppid": 901406,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-901423-1783998225926571325.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a`

Owner: `tree-sitter-python` `0.23.6`

### Source files

* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/parser.c`
* `/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/src/scanner.c`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901454,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901457,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 901458,
  "ppid": 901457,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 901455,
  "ppid": 901454,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
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
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 901460,
  "ppid": 901444,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
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
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
      "name": "aho-corasick",
      "version": "1.1.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
    },
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
      "name": "regex",
      "version": "1.13.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
      "name": "regex-automata",
      "version": "0.4.15",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
      "name": "regex-syntax",
      "version": "0.8.11",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
      "name": "streaming-iterator",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
      "name": "tree-sitter",
      "version": "0.24.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
      "name": "tree-sitter-language",
      "version": "0.1.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
      "name": "tree-sitter-python",
      "version": "0.23.6",
      "manifest_path": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6"
    }
  ],
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "kind": "exec",
  "pid": 901345,
  "ppid": 901330,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:9bf8f42bd9eab08a:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
  "pid": 901345,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:04d242bb52149c08:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
  "pid": 901345,
  "sha256": "da99707d1d8127a1f25af4f3ba373e5e750453a5f3cf905bff78742f1d51481e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "used:cc:d9861ad91616b5cc:22a29f0d0c58fcfa:085e3bf50b18abef",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
  "pid": 901345,
  "sha256": "77ac94236c6fa2d2c7f071d002442abdff45a87fd63834eafb9403a64fea154d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "cargo_pkg_name": "tree-sitter-language",
  "cargo_pkg_version": "0.1.7",
  "context_path": "/tmp/native-trace-901310-1783998223146/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-901310-1783998223146/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 901345,
  "ppid": 901330,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril",
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-901345-1783998225305967063.map",
  "pid": 901345,
  "ppid": 901330,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-901345-1783998225305967063.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "exit_code": 0,
  "kind": "exec",
  "pid": 901423,
  "ppid": 901406,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:5a70cc41ae9fb6ba:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
  "pid": 901423,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:02bef29bc0329b78:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "55812ff819a03c0a2f8f1957b998b2c66d7765f98452d93f93c5628745c4888f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:58ca91704adbd35b:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "cc4aba648348b4893da6fef4dd08519ca8993fe93d5fd04c229fcc75c14b6152",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:904cef440216b69c:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "a1f16abe885ed0bf044cbb9e936aa882fc65ae429f2a96ce28ce71f1c0b18131",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:f40610ded13a8d51:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "e6477ca72064007faa4f70323508f957e6d25f02d34b13d6e0af066f4e373a6d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:321053ab68994532:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "10bf8325a62f2066950be90f3e73a896778461c201e1578c88bad7ed4fb93b05",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:3f4f80782a352fc0:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "b8af9e03fc6be9bf7c26a98006505371e22833ceb0cca52d79027b912830b5e0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:7dab1b370270bfe4:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "ff20986d363de6c18d372c6049fe320d4ed1c31d9264403dc6e1844944cef23f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:231102dc99bd3ee7:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "de4dc5613afaf72fe9f0aa7effd1bec5227ab1ab8fbd1311a4373e875e3264b2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:391feb162071a070:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "17b2a547dd1c5cb53ec95ec2a4666c554207db8b0512802cbaead14ff563f380",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:ba29acccaf1eff52:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "f711411c268f6b2dbd4b2777a4e389c5a0afb82d5824fecddfc581d5b700d855",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:02c8e755a22d31ee:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "f7307f959206df8292ec317ee84db132555bf64053b0982c442c7ea606680a01",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "used:cc:265f2d13418f1b7d:b0a1fea503bb71f1:3182a325c58917ab",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
  "pid": 901423,
  "sha256": "9386b4f9c0230a28c972e746304a3c8583347cbdc5113a5504ca39e488d6a8f4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
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
  "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "cargo_pkg_name": "tree-sitter-python",
  "cargo_pkg_version": "0.23.6",
  "context_path": "/tmp/native-trace-901310-1783998223146/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-901310-1783998223146/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 901423,
  "ppid": 901406,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
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
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
      "kind": "object",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-901423-1783998225926571325.map",
  "pid": 901423,
  "ppid": 901406,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-901423-1783998225926571325.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 26

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

#### Record 27

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 66,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 67,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "0.084   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            901321 901310   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.095   rustc            901322 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.113   rustc            901330 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n0.113   rustc            901331 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.114   rustc            901332 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n0.152   cc               901345 901330   0 /tmp/native-trace-901310-1783998223146/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.153   cc               901346 901345   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.155   collect2         901347 901346   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.156   ld.lld           901348 901347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n0.158   rust-lld         901348 901347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.175   rustc            901371 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.193   build-script-bu  901377 901321   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n0.195   rustc            901379 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n0.733   rustc            901406 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d7d81c85968d19a9 ...\n0.773   cc               901423 901406   0 /tmp/native-trace-901310-1783998223146/shims/cc -m64 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rc -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n0.773   cc               901424 901423   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rc -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n0.775   collect2         901425 901424   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.776   ld.lld           901426 901425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311 ...\n0.777   rust-lld         901426 901425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.833   build-script-bu  901444 901321   0 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build\n0.834   riscv64-linux-g  901445 901444   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil\n0.836   cc1              901446 901445   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 8675608614110010475detect_compiler_family.c -dumpbase-ext .c\n0.841   riscv64-linux-g  901447 901444   0 /usr/bin/riscv64-linux-gnu-gcc -?\n0.844   riscv64-linux-g  901448 901444   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami\n0.846   cc1              901449 901448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 14933250904712164707detect_compiler_family.c -dumpbase-ext .c\n0.851   riscv64-linux-g  901450 901444   0 /usr/bin/riscv64-linux-gnu-gcc \n0.853   riscv64-linux-g  901451 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check -c /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c\n0.854   cc1              901452 901451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase flag_check.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -O0 -Wall ...\n0.860   as               901453 901451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check /tmp/ccodoZTH.s\n0.862   riscv64-linux-g  901454 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o -c src/parser.c ...\n0.863   cc1              901455 901454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n1.122   as               901456 901454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o /tmp/ccZcseuy.s\n1.162   riscv64-linux-g  901457 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o -c src/scanner.c ...\n1.163   cc1              901458 901457   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/scanner.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase ea708c7824d36062-scanner.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n1.189   as               901459 901457   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o /tmp/ccelXsaB.s\n1.196   riscv64-linux-g  901460 901444   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o\n1.214   riscv64-linux-g  901461 901444   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a\n1.234   rustc            901463 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_python --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5949922ab0ef73fc ...\n2.110   runc             901470 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2591555957 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n2.114   exe              901477 901470   0 /proc/self/exe init\n2.137   etcdctl          901480 901470   0 /usr/local/bin/etcdctl endpoint health\n2.996   16               901495 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n3.013   frpc             901495 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.557  runc             901501 900823   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 --log-format json --systemd-cgroup kill --all 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7 9\n10.576  runc             901508 900823   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 --log-format json --systemd-cgroup delete 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7\n10.740  containerd-shim  901514 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 delete\n10.743  runc             901522 901514   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae --log-format json delete --force 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7\n10.795  sh               901531 901528   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf1cea48\n10.796  ethtool          901532 901531   0 /usr/sbin/ethtool -i vethf1cea48\n10.796  sed              901533 901531   0 /usr/bin/sed -n s/^driver: //p\n10.803  systemd-sysctl   901536 901528   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf1cea48 --prefix=/net/ipv4/neigh/vethf1cea48 --prefix=/net/ipv6/conf/vethf1cea48 --prefix=/net/ipv6/neigh/vethf1cea48\n15.578  runc             901539 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process4096272055 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.583  exe              901546 901539   0 /proc/self/exe init\n15.601  curl             901549 901539   0 /usr/bin/curl -f http://localhost:9091/healthz\n17.720  sh               901556 2147557   0 /bin/sh -c which ps\n17.721  which            901556 2147557   0 /usr/bin/which ps\n17.724  sh               901557 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.725  ps               901557 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.755  sh               901558 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.756  cpuUsage.sh      901558 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.758  sed              901559 901558   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.761  cat              901560 901558   0 /usr/bin/cat /proc/2240539/stat\n17.763  cat              901561 901558   0 /usr/bin/cat /proc/4193716/stat\n17.764  sleep            901562 901558   0 /usr/bin/sleep 1\n18.247  16               901563 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n18.262  frpc             901563 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901377,
  "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "pid": 901377,
  "ppid": 901321,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build",
  "pid": 901444,
  "ppid": 901321,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out"
}
```

#### Record 30

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901445,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-E",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "8675608614110010475detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 901446,
  "ppid": 901445,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 32

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901447,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901448,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-E",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "14933250904712164707detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 901449,
  "ppid": 901448,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901450,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check",
    "-c",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901451,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "flag_check.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-O0",
    "-Wall",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 901452,
  "ppid": 901451,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check",
    "/tmp/ccodoZTH.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 901453,
  "ppid": 901451,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 39

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "-c",
    "src/parser.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901454,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 40

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 901455,
  "ppid": 901454,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 41

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/tmp/ccZcseuy.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 901456,
  "ppid": 901454,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 42

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-g",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-std=c11",
    "-I",
    "src",
    "-Wall",
    "-Wextra",
    "-Wno-unused-value",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
    "-c",
    "src/scanner.c",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 901457,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 43

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 901458,
  "ppid": 901457,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 44

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
    "/tmp/ccelXsaB.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 901459,
  "ppid": 901457,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 45

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 901460,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "sD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 901444,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 901461,
  "ppid": 901444,
  "root_cargo_pid": 901321,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "crate": "tree-sitter-language",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "event_id": "bsrun:9216784ad2aeda3e:28bb85b0dc13bc9f:6e85cc7cb4cad71c",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
  "out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
  "success": true,
  "target": null,
  "version": "0.1.7",
  "_owner": {
    "crate": "tree-sitter-language",
    "version": "0.1.7",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
    "source": "cwd_prefix"
  }
}
```

#### Record 48

```json
{
  "crate": "tree-sitter-python",
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "event_id": "bsrun:6228f32fe4617042:fe733e3f8f41a5aa:a89ddf9778d0c75f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
  "success": true,
  "target": null,
  "version": "0.23.6",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  }
}
```

#### Record 49

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "flag_check.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-O0",
    "-Wall",
    "..."
  ],
  "src": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 901452,
  "ppid": 901451,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 50

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/parser.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-parser.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/parser.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 901455,
  "ppid": 901454,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 51

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "real_tool": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-I",
    "src",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/scanner.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
    "-dumpbase",
    "ea708c7824d36062-scanner.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "..."
  ],
  "src": "src/scanner.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 901458,
  "ppid": 901457,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 52

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 901460,
  "ppid": 901444,
  "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "root_cargo_pid": 901321,
  "build_script_root_pid": 901444,
  "build_script_related": true,
  "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
  "_owner": {
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
    "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
  "_build_script_out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:04:08.766716+00:00",
  "crate": "tree-sitter-python",
  "version": "0.23.6",
  "architecture": "riscv64",
  "duration_seconds": 29.692516630049795,
  "trace_record_count": 48,
  "trace_owner_summary": {
    "owner_package_count": 12,
    "owner_packages": [
      {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml"
      },
      {
        "crate": "streaming-iterator",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml"
      },
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.15",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml"
      },
      {
        "crate": "regex-syntax",
        "version": "0.8.11",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml"
      },
      {
        "crate": "aho-corasick",
        "version": "1.1.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml"
      },
      {
        "crate": "tree-sitter",
        "version": "0.24.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "regex",
        "version": "1.13.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml"
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
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "manifest_path": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 21,
    "owners": [
      {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
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
      },
      {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
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
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#aho-corasick@1.1.4",
          "name": "aho-corasick",
          "version": "1.1.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4"
        },
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex@1.13.0",
          "name": "regex",
          "version": "1.13.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.15",
          "name": "regex-automata",
          "version": "0.4.15",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-syntax@0.8.11",
          "name": "regex-syntax",
          "version": "0.8.11",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#streaming-iterator@0.1.9",
          "name": "streaming-iterator",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/streaming-iterator-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter@0.24.7",
          "name": "tree-sitter",
          "version": "0.24.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-0.24.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
          "name": "tree-sitter-language",
          "version": "0.1.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
          "name": "tree-sitter-python",
          "version": "0.23.6",
          "manifest_path": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6"
        }
      ],
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "kind": "exec",
      "pid": 901345,
      "ppid": 901330,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:9bf8f42bd9eab08a:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
      "pid": 901345,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:04d242bb52149c08:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
      "pid": 901345,
      "sha256": "da99707d1d8127a1f25af4f3ba373e5e750453a5f3cf905bff78742f1d51481e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "used:cc:d9861ad91616b5cc:22a29f0d0c58fcfa:085e3bf50b18abef",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
      "pid": 901345,
      "sha256": "77ac94236c6fa2d2c7f071d002442abdff45a87fd63834eafb9403a64fea154d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "cargo_pkg_name": "tree-sitter-language",
      "cargo_pkg_version": "0.1.7",
      "context_path": "/tmp/native-trace-901310-1783998223146/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-901310-1783998223146/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 901345,
      "ppid": 901330,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril",
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
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
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6a-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-901345-1783998225305967063.map",
      "pid": 901345,
      "ppid": 901330,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-901345-1783998225305967063.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "exit_code": 0,
      "kind": "exec",
      "pid": 901423,
      "ppid": 901406,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:5a70cc41ae9fb6ba:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
      "pid": 901423,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:02bef29bc0329b78:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "55812ff819a03c0a2f8f1957b998b2c66d7765f98452d93f93c5628745c4888f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:58ca91704adbd35b:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "cc4aba648348b4893da6fef4dd08519ca8993fe93d5fd04c229fcc75c14b6152",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:904cef440216b69c:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "a1f16abe885ed0bf044cbb9e936aa882fc65ae429f2a96ce28ce71f1c0b18131",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:f40610ded13a8d51:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "e6477ca72064007faa4f70323508f957e6d25f02d34b13d6e0af066f4e373a6d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:321053ab68994532:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "10bf8325a62f2066950be90f3e73a896778461c201e1578c88bad7ed4fb93b05",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:3f4f80782a352fc0:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "b8af9e03fc6be9bf7c26a98006505371e22833ceb0cca52d79027b912830b5e0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:7dab1b370270bfe4:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "ff20986d363de6c18d372c6049fe320d4ed1c31d9264403dc6e1844944cef23f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:231102dc99bd3ee7:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "de4dc5613afaf72fe9f0aa7effd1bec5227ab1ab8fbd1311a4373e875e3264b2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:391feb162071a070:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "17b2a547dd1c5cb53ec95ec2a4666c554207db8b0512802cbaead14ff563f380",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:ba29acccaf1eff52:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "f711411c268f6b2dbd4b2777a4e389c5a0afb82d5824fecddfc581d5b700d855",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:02c8e755a22d31ee:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "f7307f959206df8292ec317ee84db132555bf64053b0982c442c7ea606680a01",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "used:cc:265f2d13418f1b7d:b0a1fea503bb71f1:3182a325c58917ab",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
      "pid": 901423,
      "sha256": "9386b4f9c0230a28c972e746304a3c8583347cbdc5113a5504ca39e488d6a8f4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
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
      "output": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "cargo_pkg_name": "tree-sitter-python",
      "cargo_pkg_version": "0.23.6",
      "context_path": "/tmp/native-trace-901310-1783998223146/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-901310-1783998223146/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 901423,
      "ppid": 901406,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
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
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311",
          "kind": "object",
          "path": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-901423-1783998225926571325.map",
      "pid": 901423,
      "ppid": 901406,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-901423-1783998225926571325.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
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
      "parsed_event_count": 66,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 67,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "0.084   TIME(s) PCOMM            PID    PPID   RET ARGS\ncargo            901321 901310   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n0.095   rustc            901322 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n0.113   rustc            901330 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n0.113   rustc            901331 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.114   rustc            901332 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n0.152   cc               901345 901330   0 /tmp/native-trace-901310-1783998223146/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.153   cc               901346 901345   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustc8O0Ril/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n0.155   collect2         901347 901346   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.156   ld.lld           901348 901347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n0.158   rust-lld         901348 901347   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjJ4Ejc.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.175   rustc            901371 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n0.193   build-script-bu  901377 901321   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n0.195   rustc            901379 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n0.733   rustc            901406 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=d7d81c85968d19a9 ...\n0.773   cc               901423 901406   0 /tmp/native-trace-901310-1783998223146/shims/cc -m64 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rc -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n0.773   cc               901424 901423   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/rustc4K61EP/symbols.o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.0x73k4246xykgv94hti1jxfr8.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.100ui1x7m1t3vt5mlf0y94f7k.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.12v5avvf71v6ppyxv8adddekt.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.17dp268w9qkrbfn830rbaeesm.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.5354ybxjvnk2qcisbwopae2zc.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.6sew81wmis9az8b1vcwm0wosj.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.ai2ybbhi9pbwv6n6nt5sax71x.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.bl7ioju3khow33h515nfzd7e5.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.c1szprmjp9w17j2avrv5rcv6i.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.dip1hy3tk3iz53ht26a5ezd47.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.e92cy9puz42f2l4av17rab49b.10e4xgr.rc /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311.a743dtcprhmilvkxbsofz9dy8.10e4xgr.rc -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n0.775   collect2         901425 901424   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n0.776   ld.lld           901426 901425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build_script_build-aa2e09fbaf36d311 ...\n0.777   rust-lld         901426 901425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccpAiLyU.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n0.833   build-script-bu  901444 901321   0 /target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build\n0.834   riscv64-linux-g  901445 901444   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil\n0.836   cc1              901446 901445   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 8675608614110010475detect_compiler_family.c -dumpbase-ext .c\n0.841   riscv64-linux-g  901447 901444   0 /usr/bin/riscv64-linux-gnu-gcc -?\n0.844   riscv64-linux-g  901448 901444   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami\n0.846   cc1              901449 901448   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 14933250904712164707detect_compiler_family.c -dumpbase-ext .c\n0.851   riscv64-linux-g  901450 901444   0 /usr/bin/riscv64-linux-gnu-gcc \n0.853   riscv64-linux-g  901451 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check -c /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c\n0.854   cc1              901452 901451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase flag_check.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -O0 -Wall ...\n0.860   as               901453 901451   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check /tmp/ccodoZTH.s\n0.862   riscv64-linux-g  901454 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o -c src/parser.c ...\n0.863   cc1              901455 901454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n1.122   as               901456 901454   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o /tmp/ccZcseuy.s\n1.162   riscv64-linux-g  901457 901444   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o -c src/scanner.c ...\n1.163   cc1              901458 901457   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/scanner.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ -dumpbase ea708c7824d36062-scanner.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n1.189   as               901459 901457   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o /tmp/ccelXsaB.s\n1.196   riscv64-linux-g  901460 901444   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o\n1.214   riscv64-linux-g  901461 901444   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a\n1.234   rustc            901463 901321   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_python --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5949922ab0ef73fc ...\n2.110   runc             901470 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2591555957 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n2.114   exe              901477 901470   0 /proc/self/exe init\n2.137   etcdctl          901480 901470   0 /usr/local/bin/etcdctl endpoint health\n2.996   16               901495 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n3.013   frpc             901495 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n10.557  runc             901501 900823   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 --log-format json --systemd-cgroup kill --all 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7 9\n10.576  runc             901508 900823   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 --log-format json --systemd-cgroup delete 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7\n10.740  containerd-shim  901514 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53 delete\n10.743  runc             901522 901514   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae --log-format json delete --force 254b4a26beb3f9ecaeb5fb6ebce0d17d526c5e97c35a61a7102d0f41d53c3ae7\n10.795  sh               901531 901528   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf1cea48\n10.796  ethtool          901532 901531   0 /usr/sbin/ethtool -i vethf1cea48\n10.796  sed              901533 901531   0 /usr/bin/sed -n s/^driver: //p\n10.803  systemd-sysctl   901536 901528   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf1cea48 --prefix=/net/ipv4/neigh/vethf1cea48 --prefix=/net/ipv6/conf/vethf1cea48 --prefix=/net/ipv6/neigh/vethf1cea48\n15.578  runc             901539 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process4096272055 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n15.583  exe              901546 901539   0 /proc/self/exe init\n15.601  curl             901549 901539   0 /usr/bin/curl -f http://localhost:9091/healthz\n17.720  sh               901556 2147557   0 /bin/sh -c which ps\n17.721  which            901556 2147557   0 /usr/bin/which ps\n17.724  sh               901557 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.725  ps               901557 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.755  sh               901558 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.756  cpuUsage.sh      901558 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.758  sed              901559 901558   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.761  cat              901560 901558   0 /usr/bin/cat /proc/2240539/stat\n17.763  cat              901561 901558   0 /usr/bin/cat /proc/4193716/stat\n17.764  sleep            901562 901558   0 /usr/bin/sleep 1\n18.247  16               901563 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n18.262  frpc             901563 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901377,
      "build_script_target_dir": "tree-sitter-language-04f523abf8aa8aa2",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "pid": 901377,
      "ppid": 901321,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build",
      "pid": 901444,
      "ppid": 901321,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901445,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-E",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/8675608614110010475detect_compiler_famil",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "8675608614110010475detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 901446,
      "ppid": 901445,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901447,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901448,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-E",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/14933250904712164707detect_compiler_fami",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "14933250904712164707detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 901449,
      "ppid": 901448,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901450,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check",
        "-c",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901451,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
        "-dumpbase",
        "flag_check.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-O0",
        "-Wall",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 901452,
      "ppid": 901451,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/flag_check",
        "/tmp/ccodoZTH.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 901453,
      "ppid": 901451,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
        "-c",
        "src/parser.c",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901454,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "src/parser.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
        "-dumpbase",
        "ea708c7824d36062-parser.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 901455,
      "ppid": 901454,
      "root_cargo_pid": 901321,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
        "/tmp/ccZcseuy.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 901456,
      "ppid": 901454,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-g",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-std=c11",
        "-I",
        "src",
        "-Wall",
        "-Wextra",
        "-Wno-unused-value",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
        "-c",
        "src/scanner.c",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 901457,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
        "-quiet",
        "-I",
        "src",
        "-imultilib",
        ".",
        "-imultiarch",
        "riscv64-linux-gnu",
        "src/scanner.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/",
        "-dumpbase",
        "ea708c7824d36062-scanner.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 901458,
      "ppid": 901457,
      "root_cargo_pid": 901321,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o",
        "/tmp/ccelXsaB.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 901459,
      "ppid": 901457,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cqD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-parser.o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/ea708c7824d36062-scanner.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 901460,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "sD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-python-d893b7dc18556f5a/out/libtree-sitter-python.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 901444,
      "build_script_target_dir": "tree-sitter-python-aa2e09fbaf36d311",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 901461,
      "ppid": 901444,
      "root_cargo_pid": 901321,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "tree-sitter-language",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "event_id": "bsrun:9216784ad2aeda3e:28bb85b0dc13bc9f:6e85cc7cb4cad71c",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
      "out_dir": "/target/debug/build/tree-sitter-language-04f523abf8aa8aa2/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
      "success": true,
      "target": null,
      "version": "0.1.7",
      "_owner": {
        "crate": "tree-sitter-language",
        "version": "0.1.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#tree-sitter-language@0.1.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "tree-sitter-python",
      "cwd": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "event_id": "bsrun:6228f32fe4617042:fe733e3f8f41a5aa:a89ddf9778d0c75f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
      "out_dir": "/target/debug/build/tree-sitter-python-aa2e09fbaf36d311/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
      "success": true,
      "target": null,
      "version": "0.23.6",
      "_owner": {
        "crate": "tree-sitter-python",
        "version": "0.23.6",
        "package_id": "path+file:///tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6#tree-sitter-python@0.23.6",
        "manifest_dir": "/tmp/crate-build-riscv64-76u37nr7/src/tree-sitter-python-0.23.6",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 3566,
    "crate": "tree-sitter-python",
    "version": "0.23.6",
    "crate_id": "305712",
    "version_id": "1383718",
    "downloads": 2729684,
    "cumulative_downloads": 108674825778,
    "cumulative_share_of_global": 0.4063100853684485,
    "status": "ok",
    "has_build_script": true,
    "build_script_path": "bindings/rust/build.rs",
    "build_script_exists": true,
    "package_build_field": "bindings/rust/build.rs",
    "build_script_reason": "package_build_path",
    "download_source": "local"
  }
}
```
