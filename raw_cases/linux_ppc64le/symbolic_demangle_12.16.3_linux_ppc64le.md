# `symbolic-demangle` `12.16.3`

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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
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
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e",
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
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-9d2fae39757f538b.rlib(shlex-9d2fae39757f538b.shlex.1ceebad2f47cb4e6-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-476911-1783994562657606467.map",
  "pid": 476911,
  "ppid": 476729,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-476911-1783994562657606467.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a`

Owner: `symbolic-demangle` `12.16.3`

### Source files

* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/src/swiftdemangle.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Context.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/CrashReporter.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Demangler.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Errors.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/ManglingUtils.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/NodeDumper.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/NodePrinter.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Punycode.cpp`
* `/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/vendor/swift/lib/Demangling/Remangler.cpp`

### Source acquisition records

_None._

### Source preparation records

#### Record 1

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "-c",
    "src/swiftdemangle.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477514,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 2

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "-c",
    "vendor/swift/lib/Demangling/CrashReporter.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478171,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 3

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "-c",
    "vendor/swift/lib/Demangling/Demangler.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478182,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 4

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "-c",
    "vendor/swift/lib/Demangling/Errors.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478688,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 5

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "-c",
    "vendor/swift/lib/Demangling/NodeDumper.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478850,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 6

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "-c",
    "vendor/swift/lib/Demangling/NodePrinter.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 479028,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 7

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "-c",
    "vendor/swift/lib/Demangling/Punycode.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 479496,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

### Compilation records

#### Record 1

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Punycode.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Punycode.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Punycode.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479497,
  "ppid": 479496,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 2

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Context.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Context.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Context.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477823,
  "ppid": 477822,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 3

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Demangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Demangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Demangler.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478183,
  "ppid": 478182,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 4

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/CrashReporter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "CrashReporter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/CrashReporter.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478173,
  "ppid": 478171,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 5

```json
{
  "event": "compile",
  "tool": "/usr/bin/powerpc64le-linux-gnu-g++",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-g++",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "-c",
    "vendor/swift/lib/Demangling/ManglingUtils.cpp"
  ],
  "src": "vendor/swift/lib/Demangling/ManglingUtils.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "pid": 478705,
  "ppid": 477218,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 6

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodePrinter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodePrinter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/NodePrinter.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479034,
  "ppid": 479028,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 7

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodeDumper.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodeDumper.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/NodeDumper.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478851,
  "ppid": 478850,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 8

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Remangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Remangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Remangler.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479700,
  "ppid": 479695,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 9

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "src/swiftdemangle.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "swiftdemangle.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "..."
  ],
  "src": "src/swiftdemangle.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477518,
  "ppid": 477514,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 10

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Errors.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Errors.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Errors.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478689,
  "ppid": 478688,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
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
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 480925,
  "ppid": 477218,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
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
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.7.0",
      "name": "bitflags",
      "version": "2.7.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#bstr@1.11.3",
      "name": "bstr",
      "version": "1.11.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.7",
      "name": "cc",
      "version": "1.2.7",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
      "name": "cfg-if",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#console@0.15.10",
      "name": "console",
      "version": "0.15.10",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
      "name": "cpp_demangle",
      "version": "0.4.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#debugid@0.8.0",
      "name": "debugid",
      "version": "0.8.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#encode_unicode@1.0.0",
      "name": "encode_unicode",
      "version": "1.0.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
      "name": "libc",
      "version": "0.2.169",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
      "name": "memchr",
      "version": "2.7.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.5",
      "name": "memmap2",
      "version": "0.9.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#msvc-demangler@0.10.1",
      "name": "msvc-demangler",
      "version": "0.10.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
      "name": "once_cell",
      "version": "1.20.2",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
      "name": "proc-macro2",
      "version": "1.0.92",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
      "name": "quote",
      "version": "1.0.38",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
      "name": "regex-automata",
      "version": "0.4.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.24",
      "name": "rustc-demangle",
      "version": "0.1.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
      "name": "serde",
      "version": "1.0.217",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
      "name": "serde_derive",
      "version": "1.0.217",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
      "name": "shlex",
      "version": "1.3.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar@2.6.0",
      "name": "similar",
      "version": "2.6.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar-asserts@1.6.0",
      "name": "similar-asserts",
      "version": "1.6.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#stable_deref_trait@1.2.0",
      "name": "stable_deref_trait",
      "version": "1.2.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#symbolic-common@12.16.3",
      "name": "symbolic-common",
      "version": "12.16.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
      "name": "symbolic-demangle",
      "version": "12.16.3",
      "manifest_path": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
      "name": "syn",
      "version": "2.0.96",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
      "name": "unicode-ident",
      "version": "1.0.14",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.12.0",
      "name": "unicode-segmentation",
      "version": "1.12.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#uuid@1.11.1",
      "name": "uuid",
      "version": "1.11.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
      "name": "windows-sys",
      "version": "0.59.0",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
      "name": "windows-targets",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
      "name": "windows_aarch64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
      "name": "windows_aarch64_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
      "name": "windows_i686_gnu",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
      "name": "windows_i686_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
      "name": "windows_i686_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
      "name": "windows_x86_64_gnu",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
      "name": "windows_x86_64_gnullvm",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
      "name": "windows_x86_64_msvc",
      "version": "0.52.6",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6"
    }
  ],
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "exit_code": 0,
  "kind": "exec",
  "pid": 474403,
  "ppid": 473506,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:6571891f52e3536e:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
  "pid": 474403,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:d0467ef2d389a945:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
  "pid": 474403,
  "sha256": "ea7f2554f1b4cd309372a002ade6053e157f7f1622f01c6b74c51110a1dc693b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:70f8f6fef722d902:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
  "pid": 474403,
  "sha256": "e3b553ac54e07e11246124a7befaf0eeb7668b7cfbed742949808375dd6b5f11",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:aa1d2fb22d061ed4:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
  "pid": 474403,
  "sha256": "0a571c2193259c2eeef4d94a385050e9bc3a9ace81785e9932284637fa2856bb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:25bfd95f0fd83bb8:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
  "pid": 474403,
  "sha256": "30705f3dcde6630c6e1ac8fae3da507a2008ecf70b27bc3c3bde708d71289a22",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:c67c164f2d01a433:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
  "pid": 474403,
  "sha256": "ee49c494b141218e666f976656595196367bf5f3953bfe215f8655b5b77976d6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "used:cc:6085563ddc1c4f22:8ab38072045dc3a7:56ebb7935a6ee919",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
  "pid": 474403,
  "sha256": "2cb481fbfc9183493aa4b7d7736c5b040df5956c5011b4ed442bd15307c60794",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
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
  "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "cargo_pkg_name": "cpp_demangle",
  "cargo_pkg_version": "0.4.4",
  "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 474403,
  "ppid": 473506,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd",
    "/target/debug/build/cpp_demangle-bdc218a092b7c581",
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
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
      "kind": "object",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-474403-1783994556460243519.map",
  "pid": 474403,
  "ppid": 473506,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-474403-1783994556460243519.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "exit_code": 0,
  "kind": "exec",
  "pid": 474495,
  "ppid": 473499,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:fec36c6ac9ebcbbe:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
  "pid": 474495,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:84c812ac47ba682b:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
  "pid": 474495,
  "sha256": "19c425fb8fba4c31176d2695c773b17b98b7431da39bfdd7b1322ecab0df9782",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:cbb1afb8530ae646:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
  "pid": 474495,
  "sha256": "3e3a170f8d462df55f8d77f10b199a8eb935ebf33852321e5ee90a3422b30bad",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:a77d00cac4eaa8d8:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
  "pid": 474495,
  "sha256": "b6f29f5fb9eb205b9b1ac80bbdf9eb3ccb387c5c1e675600e5aad44b4813f047",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:381e15ce3d5f56b1:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
  "pid": 474495,
  "sha256": "11b8f309f2702d788a41c710b99d4fd070b78773b4f72026f29fadc55992ec09",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "used:cc:5588d86099c98adc:2ddab823d039700f:4fc77846b52fff44",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
  "pid": 474495,
  "sha256": "2faf50a7df8593ce0b2519386fd7191478995438688311a3228eed1428d4f9f3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
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
  "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.169",
  "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 474495,
  "ppid": 473499,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6",
    "/target/debug/build/libc-08068d25dbed1dac",
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
      "directory": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-08068d25dbed1dac",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-08068d25dbed1dac",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-08068d25dbed1dac",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-08068d25dbed1dac",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-08068d25dbed1dac",
      "kind": "object",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-474495-1783994556641591610.map",
  "pid": 474495,
  "ppid": 473499,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-474495-1783994556641591610.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "exit_code": 0,
  "kind": "exec",
  "pid": 476911,
  "ppid": 476729,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:62cd40011225de4b:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
  "pid": 476911,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:71ca03e4089b7b8e:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "6c644dc45f097b1985fc2486a2514db6bd7d2976d9985e9e29748fd8bbe16767",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:b5c1e687fbcd9c3a:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "9dec8a4a0e61bb2c80b17ff89653dba973f818d722bb7337f1a546427f5fad67",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:7620c878ae7605c0:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "3e364c8bfc27a2900e209f6a3ea5de55ebe9430be4a9e03bba0933429e68e2f6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:f6038f7e212a6970:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "a82f9748b1f68fb5c71d2e770e391729bca37e29c49a2cd37f99a36544783ac4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:300e9f39343ee4ca:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "b95f3c56e36f7cb744b26064b1d973f557d5955c40daab06aa16e87f3990324e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 30

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:b4aa5fd9ad3482fd:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "229229247eff52a9f027309dadaa6358e09a543fcaa365b6f5cc53ff806dbb9a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 31

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:b264ef76b240393c:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "e323e034922eb359f50ac061cafb261f26608a8b2d28648b2c9beab3d99de6ba",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 32

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:246e5025507db594:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "7423ce28af82ee4172f9a7fc69b334184cc0f38f61725733a9f6385d42dbeaa9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 33

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:9c41dbab8b7b5b03:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "435dde7fea076eb718ebf0b271d1b37705124878c779eb6c9215a187132eba92",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 34

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:d748bd0a5f43462c:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "1525777c4027bc55aa9f9e1a0625359adf58e9edc30f0b9d125bc44f9a548153",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 35

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:d14f2380e73f9a96:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "46fc4cef204a339e8b0ca79f03182e12824285f3c4e3d653c99f8428231ef5e2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 36

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "used:cc:a5e35b52292e6c2a:9e0d7d7499fffbab:25d7c0844c10b0e7",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
  "pid": 476911,
  "sha256": "d054befa8afa240f9a85cbe1e3407054b07fa8c97a852713cc485a77c2ebf83a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 37

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
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
  "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 38

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "cargo_pkg_name": "symbolic-demangle",
  "cargo_pkg_version": "12.16.3",
  "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 476911,
  "ppid": 476729,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 39

```json
{
  "argv": [
    "cc",
    "-m64",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
    "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
    "/target/debug/build/symbolic-demangle-adec670d1917b46e",
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
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
      "kind": "object",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.10.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.11.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.12.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.13.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.14.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.15.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libshlex-9d2fae39757f538b.rlib(shlex-9d2fae39757f538b.shlex.1ceebad2f47cb4e6-cgu.0.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-476911-1783994562657606467.map",
  "pid": 476911,
  "ppid": 476729,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-476911-1783994562657606467.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cargo_manifest_dir"
  }
}
```

#### Record 40

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

#### Record 41

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 2,
  "parsed_event_count": 4227,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 4229,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "nu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_header.c -o rdkafka_header.o\n38.289  cc1              487868 487865   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_header.d -MP -MQ rdkafka_header.o rdkafka_header.c -quiet -dumpbase rdkafka_header.c -dumpbase-ext ...\n38.330  as               487869 487726   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o tinycthread_extra.o /tmp/ccxP8qfM.s\n38.349  rustc            487871 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n38.350  cc1              487866 487863   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -dumpbase-ext ...\n38.387  cc               487877 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdstring.c -o rdstring.o\n38.393  cc               487879 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_event.c -o rdkafka_event.o\n38.393  cc               487880 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n38.396  cc               487878 487877   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdstring.c -o rdstring.o\n38.398  cc               487881 487880   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n38.409  cc               487883 487879   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_event.c -o rdkafka_event.o\n38.411  cc1              487882 487878   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdstring.d -MP -MQ rdstring.o rdstring.c -quiet -dumpbase rdstring.c -mtune=generic ...\n38.416  cc1              487884 487881   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_admin.d -MP -MQ rdkafka_admin.o rdkafka_admin.c -quiet -dumpbase rdkafka_admin.c -dumpbase-ext ...\n38.418  cc1              487885 487883   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_event.d -MP -MQ rdkafka_event.o rdkafka_event.c -quiet -dumpbase rdkafka_event.c -mtune=generic ...\n38.465  cc               487887 483668   0 /tmp/native-trace-469541-1783994548054/shims/cc -Wl,--version-script=/target/debug/deps/rustcy3HUg3/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcy3HUg3/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n38.465  as               487893 487836   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdports.o /tmp/ccrb1vA5.s\n38.471  cc               487895 487887   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcy3HUg3/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcy3HUg3/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n38.482  collect2         487897 487895   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcy3HUg3/raw-dylibs ...\n38.491  as               487898 487737   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdregex.o /tmp/ccEDBZ2x.s\n38.498  ld.lld           487899 487897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcy3HUg3/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n38.507  rust-lld         487899 487897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n38.529  cc               487901 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n38.540  cc               487903 487901   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n38.546  cc1              487904 487903   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl_plain.d -MP -MQ rdkafka_sasl_plain.o rdkafka_sasl_plain.c -quiet -dumpbase rdkafka_sasl_plain.c -mtune=generic ...\n38.564  cc               487905 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n38.569  cc               487906 487905   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n38.588  cc1              487909 487906   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_interceptor.d -MP -MQ rdkafka_interceptor.o rdkafka_interceptor.c -quiet -dumpbase rdkafka_interceptor.c -mtune=generic ...\n38.606  as               487907 485675   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_msg.o /tmp/ccnOb9aD.s\n38.683  as               487926 487423   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdstring.o /tmp/ccaR5VqO.s\n38.733  cross            487927 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n38.734  rustc            487930 487927   0 /home/xmoe/.cargo/bin/rustc --print target-list\n38.744  as               487928 487689   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_sasl_plain.o /tmp/cccjLDEl.s\n38.746  cc               487940 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n38.748  rustc            487930 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n38.760  cc               487941 487940   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n38.782  cc1              487945 487941   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_writer.d -MP -MQ rdkafka_msgset_writer.o rdkafka_msgset_writer.c -quiet -dumpbase rdkafka_msgset_writer.c -mtune=generic ...\n38.807  rustc            487946 487927   0 /home/xmoe/.cargo/bin/rustc -vV\n38.820  cc               487955 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n38.831  cc               487956 487955   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n38.844  as               487957 487850   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdavl.o /tmp/ccCprUl9.s\n38.847  cc1              487958 487956   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_aux.d -MP -MQ rdkafka_aux.o rdkafka_aux.c -quiet -dumpbase rdkafka_aux.c -dumpbase-ext ...\n38.863  rustc            487946 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.878  cargo            487963 487927   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n38.886  cc               487962 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n38.888  cargo            487963 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n38.889  cc               487972 487962   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n38.906  rustc            487975 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.909  as               487973 487645   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdavl.o /tmp/ccLvb3Xd.s\n38.909  cc1              487974 487972   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -mtune=generic ...\n38.921  as               487976 487848   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdlog.o /tmp/cccqDhrX.s\n38.921  rustc            487978 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n38.933  cc               487982 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_background.c -o rdkafka_background.o\n38.935  cc               487980 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata.c -o rdkafka_metadata.o\n38.939  cc               487988 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdregex.c -o rdregex.o\n38.941  rustc            487989 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n38.947  cc               487990 487988   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdregex.c -o rdregex.o\n38.953  cc1              487991 487990   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdregex.d -MP -MQ rdregex.o rdregex.c -quiet -dumpbase rdregex.c -mtune=generic ...\n38.962  cc               487987 487980   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata.c -o rdkafka_metadata.o\n38.973  as               487981 487464   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdlist.o /tmp/ccETVgbU.s\n38.983  cc1              487996 487987   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_metadata.d -MP -MQ rdkafka_metadata.o rdkafka_metadata.c -quiet -dumpbase rdkafka_metadata.c -mtune=generic ...\n38.984  cc               487986 487982   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_background.c -o rdkafka_background.o\n39.003  cc1              487998 487986   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_background.d -MP -MQ rdkafka_background.o rdkafka_background.c -quiet -dumpbase rdkafka_background.c -dumpbase-ext ...\n39.006  sh               487999 2147557   0 /bin/sh -c which ps\n39.007  which            487999 2147557   0 /usr/bin/which ps\n39.012  sh               488000 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.016  ps               488000 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.047  cc               488001 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdports.c -o rdports.o\n39.054  cc               488002 488001   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdports.c -o rdports.o\n39.070  cc1              488003 488002   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdports.d -MP -MQ rdports.o rdports.c -quiet -dumpbase rdports.c -mtune=generic ...\n39.073  sh               488005 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n39.075  cpuUsage.sh      488005 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n39.078  sed              488006 488005   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n39.083  cat              488007 488005   0 /usr/bin/cat /proc/2240539/stat\n39.085  cat              488008 488005   0 /usr/bin/cat /proc/4193716/stat\n39.087  sleep            488009 488005   0 /usr/bin/sleep 1\n39.098  rustc            488011 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.107  cross            488013 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n39.108  rustc            488017 488013   0 /home/xmoe/.cargo/bin/rustc --print target-list\n39.118  rustc            488017 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n39.118  rustc            488012 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n39.132  as               488027 485696   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_op.o /tmp/cckzzcEf.s\n39.140  rustc            488031 488013   0 /home/xmoe/.cargo/bin/rustc -vV\n39.145  rustc            488040 487927   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n39.157  rustc            488031 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.157  rustc            488040 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n39.160  cargo            488050 488013   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n39.172  docker           488063 487927   0 /usr/bin/docker --help\n39.197  docker           488075 487927   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n39.210  as               488074 485695   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_queue.o /tmp/ccPeMOpd.s\n39.218  as               488082 487681   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_sasl.o /tmp/cc3GpIbd.s\n39.221  runc             488086 1599     0 /usr/bin/runc --version\n39.228  docker-init      488091 1599     0 /usr/bin/docker-init --version\n39.230  docker           488092 487927   0 \n39.257  runc             488102 1599     0 \n39.263  docker-init      488107 1599     0 /usr/bin/docker-init --version\n39.267  as               488098 487990   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdregex.o /tmp/ccfp2JrK.s\n39.290  as               488108 487878   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdstring.o /tmp/ccduePlg.s\n39.301  rustup           488109 487927   0 \n39.303  cargo            488050 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n39.320  rustc            488118 488050   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.328  as               488119 487903   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_sasl_plain.o /tmp/ccCtG7f9.s\n39.340  rustc            488122 488050   0 \n39.340  as               488120 487691   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_interceptor.o /tmp/ccVXuDp1.s\n39.352  rustc            488128 488050   0 \n39.352  cc               488127 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_header.c -o rdkafka_header.o\n39.363  cc               488126 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata_cache.c -o rdkafka_metadata_cache.o\n39.363  cc               488129 488127   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_header.c -o rdkafka_header.o\n39.371  cc               488133 488126   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata_cache.c -o rdkafka_metadata_cache.o\n39.408  cc1              488147 488146   0 \n39.409  cc               488149 488148   0 \n39.409  cc               488146 488136   0 \n39.409  cc               488148 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl.c -o rdkafka_sasl.o\n39.409  cc1              488135 488133   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_metadata_cache.d -MP -MQ rdkafka_metadata_cache.o rdkafka_metadata_cache.c -quiet -dumpbase rdkafka_metadata_cache.c -mtune=generic ...\n39.409  cc               488136 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdavl.c -o rdavl.o\n39.409  rustup           488137 487927   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n39.412  cc1              488150 488149   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl.d -MP -MQ rdkafka_sasl.o rdkafka_sasl.c -quiet -dumpbase rdkafka_sasl.c -mtune=generic ...\n39.417  cc1              488153 488129   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_header.d -MP -MQ rdkafka_header.o rdkafka_header.c -quiet -dumpbase rdkafka_header.c -mtune=generic ...\n39.429  rustup           488156 487927   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n39.430  rustc            488155 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_executor --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.469  rustc            488169 488050   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.477  uname            488170 487927   0 /usr/bin/uname -r\n39.505  rustc            488172 488013   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n39.508  docker           488173 487927   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n39.513  rustc            488172 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n39.531  docker           488194 488013   0 /usr/bin/docker --help\n39.559  cc               488208 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n39.567  rustc            488207 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.602  cc               488212 488208   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n39.602  cc1              488213 488212   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl_plain.d -MP -MQ rdkafka_sasl_plain.o rdkafka_sasl_plain.c -quiet -dumpbase rdkafka_sasl_plain.c -mtune=generic ...\n39.603  docker           488214 488013   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n39.614  rustc            488226 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n39.638  as               488232 486600   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_assignor.o /tmp/ccaXopuD.s\n39.639  runc             488236 1599     0 /usr/bin/runc --version\n39.648  systemd-sysctl   488245 488237   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf04044 --prefix=/net/ipv4/neigh/vethbf04044 --prefix=/net/ipv6/conf/vethbf04044 --prefix=/net/ipv6/neigh/vethbf04044\n39.648  docker-init      488246 1599     0 /usr/bin/docker-init --version\n39.653  docker           488248 488013   0 /usr/bin/docker info -f {{.SecurityOptions}}\n39.653  systemd-sysctl   488244 488235   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth59b42ee --prefix=/net/ipv4/neigh/veth59b42ee --prefix=/net/ipv6/conf/veth59b42ee --prefix=/net/ipv6/neigh/veth59b42ee\n39.658  cc               488247 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_idempotence.c -o rdkafka_idempotence.o\n39.671  cc               488254 488247   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_idempotence.c -o rdkafka_idempotence.o\n39.671  cc1              488256 488254   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_idempotence.d -MP -MQ rdkafka_idempotence.o rdkafka_idempotence.c -quiet -dumpbase rdkafka_idempotence.c -dumpbase-ext ...\n39.681  runc             488264 1599     0 /usr/bin/runc --version\n39.684  containerd-shim  488266 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 start\n39.692  docker-init      488282 1599     0 /usr/bin/docker-init --version\n39.692  containerd-shim  488283 488266   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 -address /var/run/docker/containerd/containerd.sock\n39.692  as               488265 488129   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_header.o /tmp/ccXIDyYd.s\n39.694  rustc            488263 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n39.695  runc             488292 488283   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06\n39.695  as               488280 488002   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdports.o /tmp/ccfdgkfC.s\n39.705  exe              488302 488292   0 /proc/self/exe init\n39.736  rustup           488321 488013   0 \n39.744  rustc            488323 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n39.785  cc               488346 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n39.788  cc               488348 488346   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n39.794  cc1              488356 488348   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_admin.d -MP -MQ rdkafka_admin.o rdkafka_admin.c -quiet -dumpbase rdkafka_admin.c -mtune=generic ...\n39.797  rustup           488362 488013   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n39.833  cc               488371 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n39.839  rustup           488373 488013   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n39.843  cc               488374 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_cert.c -o rdkafka_cert.o\n39.846  cc               488383 488374   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_cert.c -o rdkafka_cert.o\n39.862  cc               488372 488371   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n39.866  cc               488388 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n39.867  cc               488390 488388   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n39.874  rustc            488389 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_executor --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.876  cc1              488391 488390   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_writer.d -MP -MQ rdkafka_msgset_writer.o rdkafka_msgset_writer.c -quiet -dumpbase rdkafka_msgset_writer.c -mtune=generic ...\n39.910  cc1              488384 488383   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_cert.d -MP -MQ rdkafka_cert.o rdkafka_cert.c -quiet -dumpbase rdkafka_cert.c -dumpbase-ext ...\n39.910  cc1              488394 488372   0 \n39.910  uname            488393 488013   0 /usr/bin/uname -r\n39.910  docker           488399 488013   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n39.950  16               488416 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n39.981  frpc             488416 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n39.989  exe              488418 488292   0 /proc/1599/exe -exec-root=/var/run/docker eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 d7da31e8f8e1\n39.995  as               488419 485738   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_assignor.o /tmp/cc8Iog1E.s\n40.044  systemd-sysctl   488435 488310   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth75d7597 --prefix=/net/ipv4/neigh/veth75d7597 --prefix=/net/ipv6/conf/veth75d7597 --prefix=/net/ipv6/neigh/veth75d7597\n40.054  systemd-sysctl   488434 488317   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth01847bb --prefix=/net/ipv4/neigh/veth01847bb --prefix=/net/ipv6/conf/veth01847bb --prefix=/net/ipv6/neigh/veth01847bb\n40.061  containerd-shim  488436 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c start\n40.068  exe              488444 1599     0 /proc/self/exe /var/run/docker/netns/71f8de50bb57 all false\n40.069  containerd-shim  488445 488436   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c -address /var/run/docker/containerd/containerd.sock\n40.085  as               488458 487883   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_event.o /tmp/ccVpyzmC.s\n40.090  sed              488461 488005   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n40.094  cat              488463 488005   0 /usr/bin/cat /proc/2240539/stat\n40.097  cat              488465 488005   0 /usr/bin/cat /proc/4193716/stat\n40.118  runc             488475 488445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c\n40.128  exe              488482 488475   0 /proc/self/exe init\n40.150  as               488484 485405   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_assignor.o /tmp/ccT8bkdg.s\n40.155  rustc            488485 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n40.193  runc             488492 488283   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --log-format json --systemd-cgroup start eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06\n40.204  sh               488405 488283   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n40.207  cargo            488501 488405   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n40.213  cc               488504 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n40.221  cc               488506 488504   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n40.227  cargo-native-tr  488501 488405   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n40.236  cc               488508 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_txnmgr.c -o rdkafka_txnmgr.o\n40.236  cc1              488507 488506   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -mtune=generic ...\n40.240  cargo            488509 488501   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n40.244  exe              488510 488475   0 /proc/1599/exe -exec-root=/var/run/docker f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c d7da31e8f8e1\n40.253  cc               488512 488508   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_txnmgr.c -o rdkafka_txnmgr.o\n40.255  cc               488518 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n40.262  cc               488520 488518   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n40.262  cc1              488521 488512   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_txnmgr.d -MP -MQ rdkafka_txnmgr.o rdkafka_txnmgr.c -quiet -dumpbase rdkafka_txnmgr.c -dumpbase-ext ...\n40.273  rustc            488522 488509   0 \n40.281  cc1              488523 488520   0 \n40.289  exe              488528 1599     0 /proc/self/exe /var/run/docker/netns/c3e6fd3a6f95 all false\n40.292  rustc            488527 488509   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
}
```

#### Record 42

```json
{
  "argv": [
    "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 474669,
  "build_script_target_dir": "cpp_demangle-bdc218a092b7c581",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build",
  "pid": 474669,
  "ppid": 473456,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "_build_script_out_dir": "/target/debug/build/cpp_demangle-bdc218a092b7c581/out"
}
```

#### Record 43

```json
{
  "argv": [
    "/target/debug/build/libc-08068d25dbed1dac/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 474673,
  "build_script_target_dir": "libc-08068d25dbed1dac",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-08068d25dbed1dac/build-script-build",
  "pid": 474673,
  "ppid": 473456,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "_build_script_out_dir": "/target/debug/build/libc-08068d25dbed1dac/out"
}
```

#### Record 44

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 474673,
  "build_script_target_dir": "libc-08068d25dbed1dac",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 474674,
  "ppid": 474673,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "_build_script_out_dir": "/target/debug/build/libc-08068d25dbed1dac/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 45

```json
{
  "argv": [
    "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build",
  "pid": 477218,
  "ppid": 473456,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out"
}
```

#### Record 46

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/6546468493072063648detect_compiler_fami"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477223,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 47

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/6546468493072063648detect_compiler_fami",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477224,
  "ppid": 477223,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 48

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477232,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 49

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "powerpc64le-lin",
  "pid": 477283,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 50

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/8442321474154837685detect_compiler_fami",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477284,
  "ppid": 477283,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 51

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477286,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 52

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-m64",
    "-Wall",
    "-Wextra",
    "-fpermissive",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477288,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 53

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase",
    "flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477289,
  "ppid": 477288,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 54

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/tmp/ccI3INcu.o",
    "/tmp/ccZ0OaXr.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 477329,
  "ppid": 477288,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 55

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
    "-plugin",
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
    "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
    "-plugin-opt=-fresolution=/tmp/ccwfrzsv.res",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "-plugin-opt=-pass-through=-lc",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "--sysroot=/",
    "--build-id",
    "--eh-frame-hdr",
    "-m",
    "elf64lppc",
    "--hash-style=gnu",
    "--as-needed",
    "-dynamic-linker",
    "/lib64/ld64.so.2",
    "-pie",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "collect2",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
  "pid": 477333,
  "ppid": 477288,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out"
}
```

#### Record 56

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
    "-plugin",
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
    "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
    "-plugin-opt=-fresolution=/tmp/ccwfrzsv.res",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "-plugin-opt=-pass-through=-lc",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "--sysroot=/",
    "--build-id",
    "--eh-frame-hdr",
    "-m",
    "elf64lppc",
    "--hash-style=gnu",
    "--as-needed",
    "-dynamic-linker",
    "/lib64/ld64.so.2",
    "-pie",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "ld",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
  "pid": 477340,
  "ppid": 477333,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out"
}
```

#### Record 57

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-E",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/404301563908866550detect_compiler_famil"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477401,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 58

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-E",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/404301563908866550detect_compiler_famil",
    "-msecure-plt",
    "-mcpu=power8",
    "-fasynchronous-unwind-tables",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-fstack-clash-protection"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477402,
  "ppid": 477401,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 59

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477404,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 60

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-m64",
    "-Wall",
    "-Wextra",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477408,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 61

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase",
    "flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-Wno-changes-meaning",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477410,
  "ppid": 477408,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 62

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/tmp/ccCDWgFw.o",
    "/tmp/ccrmjzCA.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 477430,
  "ppid": 477408,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 63

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
    "-plugin",
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
    "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
    "-plugin-opt=-fresolution=/tmp/ccjQLqWw.res",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "-plugin-opt=-pass-through=-lc",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "--sysroot=/",
    "--build-id",
    "--eh-frame-hdr",
    "-m",
    "elf64lppc",
    "--hash-style=gnu",
    "--as-needed",
    "-dynamic-linker",
    "/lib64/ld64.so.2",
    "-pie",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "collect2",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
  "pid": 477435,
  "ppid": 477408,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out"
}
```

#### Record 64

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
    "-plugin",
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
    "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
    "-plugin-opt=-fresolution=/tmp/ccjQLqWw.res",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "-plugin-opt=-pass-through=-lc",
    "-plugin-opt=-pass-through=-lgcc_s",
    "-plugin-opt=-pass-through=-lgcc",
    "--sysroot=/",
    "--build-id",
    "--eh-frame-hdr",
    "-m",
    "elf64lppc",
    "--hash-style=gnu",
    "--as-needed",
    "-dynamic-linker",
    "/lib64/ld64.so.2",
    "-pie",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "ld",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
  "pid": 477438,
  "ppid": 477435,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out"
}
```

#### Record 65

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "-c",
    "src/swiftdemangle.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 477514,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 66

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "src/swiftdemangle.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "swiftdemangle.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477518,
  "ppid": 477514,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 67

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/tmp/ccFJwmdA.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 477796,
  "ppid": 477514,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 68

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "powerpc64le-lin",
  "pid": 477822,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 69

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Context.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Context.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 477823,
  "ppid": 477822,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 70

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/tmp/ccDxuV4O.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 478140,
  "ppid": 477822,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 71

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "-c",
    "vendor/swift/lib/Demangling/CrashReporter.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478171,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 72

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/CrashReporter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "CrashReporter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 478173,
  "ppid": 478171,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 73

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/tmp/ccxPOi6f.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 478181,
  "ppid": 478171,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 74

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "-c",
    "vendor/swift/lib/Demangling/Demangler.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478182,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 75

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Demangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Demangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 478183,
  "ppid": 478182,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 76

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/tmp/cckP2S13.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 478674,
  "ppid": 478182,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 77

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "-c",
    "vendor/swift/lib/Demangling/Errors.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478688,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 78

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Errors.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Errors.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 478689,
  "ppid": 478688,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 79

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/tmp/ccGATXFj.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 478700,
  "ppid": 478688,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 80

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "cc1plus",
  "pid": 478706,
  "ppid": 478705,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 81

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "-c",
    "vendor/swift/lib/Demangling/ManglingUtils.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478705,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 82

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/tmp/ccgV3PiD.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 478846,
  "ppid": 478705,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 83

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "-c",
    "vendor/swift/lib/Demangling/NodeDumper.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 478850,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 84

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodeDumper.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodeDumper.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 478851,
  "ppid": 478850,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 85

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/tmp/ccjD81kA.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 479012,
  "ppid": 478850,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 86

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "-c",
    "vendor/swift/lib/Demangling/NodePrinter.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 479028,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 87

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodePrinter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodePrinter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 479034,
  "ppid": 479028,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 88

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/tmp/ccwVHyV0.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 479465,
  "ppid": 479028,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 89

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "-c",
    "vendor/swift/lib/Demangling/Punycode.cpp"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-g++",
  "pid": 479496,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 90

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Punycode.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Punycode.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 479497,
  "ppid": 479496,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 91

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/tmp/ccUcVN6p.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 479689,
  "ppid": 479496,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 92

```json
{
  "argv": [],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "powerpc64le-lin",
  "pid": 479695,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 93

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Remangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Remangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "cc1plus",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "pid": 479700,
  "ppid": 479695,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 94

```json
{
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
    "-I",
    "vendor/swift/include",
    "-a64",
    "-mpower8",
    "-many",
    "-mlittle",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
    "/tmp/cc05kU0t.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
  "pid": 480880,
  "ppid": 479695,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 95

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 480925,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 96

```json
{
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "s",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 477218,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "comm": "powerpc64le-lin",
  "event": "process_exec",
  "image": "/usr/bin/powerpc64le-linux-gnu-ar",
  "pid": 480933,
  "ppid": 477218,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 97

```json
{
  "crate": "cpp_demangle",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "event_id": "bsrun:879fe768e1a13410:93fd464f0aa7863e:716a9c7a798f9e02",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
  "out_dir": "/target/debug/build/cpp_demangle-bdc218a092b7c581/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
  "success": true,
  "target": null,
  "version": "0.4.4",
  "_owner": {
    "crate": "cpp_demangle",
    "version": "0.4.4",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
    "source": "cwd_prefix"
  }
}
```

#### Record 98

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "event_id": "bsrun:506248994e02715a:3c839f80d7aba6f2:55b59efa4ce4e1e3",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-08068d25dbed1dac/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
  "out_dir": "/target/debug/build/libc-08068d25dbed1dac/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
  "success": true,
  "target": null,
  "version": "0.2.169",
  "_owner": {
    "crate": "libc",
    "version": "0.2.169",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
    "source": "cwd_prefix"
  }
}
```

#### Record 99

```json
{
  "crate": "symbolic-demangle",
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "event_id": "bsrun:8c5a927913717811:2161d06b284b92cc:e0160276b48fa4ce",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
  "success": true,
  "target": null,
  "version": "12.16.3",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  }
}
```

#### Record 100

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 474673,
  "build_script_target_dir": "libc-08068d25dbed1dac",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 474674,
  "ppid": 474673,
  "root_cargo_pid": 473456,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 101

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase",
    "flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "..."
  ],
  "src": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
  "output": "/tmp/ccI3INcu.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477289,
  "ppid": 477288,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 102

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "flag_check.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase",
    "flag_check",
    "-O0",
    "-Wall",
    "-Wextra",
    "-Wno-changes-meaning",
    "-ffunction-sections",
    "-fdata-sections",
    "..."
  ],
  "src": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
  "output": "/tmp/ccCDWgFw.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477410,
  "ppid": 477408,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 103

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "src/swiftdemangle.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "swiftdemangle.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "..."
  ],
  "src": "src/swiftdemangle.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477518,
  "ppid": 477514,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 104

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Context.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Context.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Context.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 477823,
  "ppid": 477822,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 105

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/CrashReporter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "CrashReporter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/CrashReporter.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478173,
  "ppid": 478171,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 106

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Demangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Demangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Demangler.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478183,
  "ppid": 478182,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 107

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Errors.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Errors.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Errors.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478689,
  "ppid": 478688,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 108

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodeDumper.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodeDumper.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/NodeDumper.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 478851,
  "ppid": 478850,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 109

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/NodePrinter.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "NodePrinter.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/NodePrinter.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479034,
  "ppid": 479028,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 110

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Punycode.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Punycode.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Punycode.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479497,
  "ppid": 479496,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 111

```json
{
  "event": "compile",
  "tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "real_tool": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
  "argv": [
    "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
    "-quiet",
    "-I",
    "vendor/swift/include",
    "-imultiarch",
    "powerpc64le-linux-gnu",
    "-D_GNU_SOURCE",
    "-D",
    "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-D",
    "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "vendor/swift/lib/Demangling/Remangler.cpp",
    "-msecure-plt",
    "-quiet",
    "-dumpbase",
    "Remangler.cpp",
    "-m64",
    "-mcpu=power8",
    "-auxbase-strip",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
    "..."
  ],
  "src": "vendor/swift/lib/Demangling/Remangler.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 479700,
  "ppid": 479695,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 112

```json
{
  "event": "compile",
  "tool": "/usr/bin/powerpc64le-linux-gnu-g++",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-g++",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-g++",
    "-O0",
    "-ffunction-sections",
    "-fdata-sections",
    "-fPIC",
    "-gdwarf-4",
    "-fno-omit-frame-pointer",
    "-m64",
    "-std=c++17",
    "-I",
    "vendor/swift/include",
    "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
    "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
    "-fpermissive",
    "-Wno-changes-meaning",
    "-o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "-c",
    "vendor/swift/lib/Demangling/ManglingUtils.cpp"
  ],
  "src": "vendor/swift/lib/Demangling/ManglingUtils.cpp",
  "output": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "pid": 478705,
  "ppid": 477218,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 113

```json
{
  "event": "archive",
  "tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "real_tool": "/usr/bin/powerpc64le-linux-gnu-ar",
  "argv": [
    "/usr/bin/powerpc64le-linux-gnu-ar",
    "cq",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
  ],
  "archive": "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
  "objects": [
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
    "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 480925,
  "ppid": 477218,
  "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "root_cargo_pid": 473456,
  "build_script_root_pid": 477218,
  "build_script_related": true,
  "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
  "_owner": {
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
    "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
  "_build_script_out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:03:15.849394+00:00",
  "crate": "symbolic-demangle",
  "version": "12.16.3",
  "architecture": "ppc64le",
  "duration_seconds": 50.89774186722934,
  "trace_record_count": 99,
  "trace_owner_summary": {
    "owner_package_count": 39,
    "owner_packages": [
      {
        "crate": "windows_aarch64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "unicode-segmentation",
        "version": "1.12.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.12.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0/Cargo.toml"
      },
      {
        "crate": "windows_aarch64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnullvm",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows_x86_64_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "stable_deref_trait",
        "version": "1.2.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#stable_deref_trait@1.2.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0/Cargo.toml"
      },
      {
        "crate": "windows_i686_msvc",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml"
      },
      {
        "crate": "symbolic-common",
        "version": "12.16.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#symbolic-common@12.16.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3/Cargo.toml"
      },
      {
        "crate": "windows_i686_gnu",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml"
      },
      {
        "crate": "windows-targets",
        "version": "0.52.6",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml"
      },
      {
        "crate": "msvc-demangler",
        "version": "0.10.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#msvc-demangler@0.10.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1/Cargo.toml"
      },
      {
        "crate": "rustc-demangle",
        "version": "0.1.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24/Cargo.toml"
      },
      {
        "crate": "similar-asserts",
        "version": "1.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar-asserts@1.6.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0/Cargo.toml"
      },
      {
        "crate": "encode_unicode",
        "version": "1.0.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#encode_unicode@1.0.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0/Cargo.toml"
      },
      {
        "crate": "regex-automata",
        "version": "0.4.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml"
      },
      {
        "crate": "serde_derive",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.14",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14/Cargo.toml"
      },
      {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.92",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92/Cargo.toml"
      },
      {
        "crate": "windows-sys",
        "version": "0.59.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml"
      },
      {
        "crate": "once_cell",
        "version": "1.20.2",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/Cargo.toml"
      },
      {
        "crate": "console",
        "version": "0.15.10",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#console@0.15.10",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10/Cargo.toml"
      },
      {
        "crate": "bitflags",
        "version": "2.7.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.7.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0/Cargo.toml"
      },
      {
        "crate": "debugid",
        "version": "0.8.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#debugid@0.8.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0/Cargo.toml"
      },
      {
        "crate": "memmap2",
        "version": "0.9.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.217",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml"
      },
      {
        "crate": "similar",
        "version": "2.6.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar@2.6.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0/Cargo.toml"
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
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.7.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.38",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml"
      },
      {
        "crate": "bstr",
        "version": "1.11.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#bstr@1.11.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3/Cargo.toml"
      },
      {
        "crate": "shlex",
        "version": "1.3.0",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml"
      },
      {
        "crate": "uuid",
        "version": "1.11.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#uuid@1.11.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.96",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96/Cargo.toml"
      },
      {
        "crate": "cc",
        "version": "1.2.7",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.7",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7/Cargo.toml"
      },
      {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "manifest_path": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/Cargo.toml"
      }
    ],
    "attributed_event_count": 42,
    "unattributed_event_count": 57,
    "owners": [
      {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
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
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "event_count": 12,
        "kind_counts": {
          "exec": 1,
          "used_input": 7,
          "link": 1,
          "exec_context": 1,
          "resolved_link": 1,
          "build_script_run": 1
        }
      },
      {
        "crate": "libc",
        "version": "0.2.169",
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
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bitflags@2.7.0",
          "name": "bitflags",
          "version": "2.7.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bitflags-2.7.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#bstr@1.11.3",
          "name": "bstr",
          "version": "1.11.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/bstr-1.11.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.7",
          "name": "cc",
          "version": "1.2.7",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.7"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cfg-if@1.0.0",
          "name": "cfg-if",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cfg-if-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#console@0.15.10",
          "name": "console",
          "version": "0.15.10",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/console-0.15.10"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
          "name": "cpp_demangle",
          "version": "0.4.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#debugid@0.8.0",
          "name": "debugid",
          "version": "0.8.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/debugid-0.8.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#encode_unicode@1.0.0",
          "name": "encode_unicode",
          "version": "1.0.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/encode_unicode-1.0.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
          "name": "libc",
          "version": "0.2.169",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.7.4",
          "name": "memchr",
          "version": "2.7.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.7.4"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memmap2@0.9.5",
          "name": "memmap2",
          "version": "0.9.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memmap2-0.9.5"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#msvc-demangler@0.10.1",
          "name": "msvc-demangler",
          "version": "0.10.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/msvc-demangler-0.10.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#once_cell@1.20.2",
          "name": "once_cell",
          "version": "1.20.2",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/once_cell-1.20.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.92",
          "name": "proc-macro2",
          "version": "1.0.92",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.92"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.38",
          "name": "quote",
          "version": "1.0.38",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.38"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#regex-automata@0.4.9",
          "name": "regex-automata",
          "version": "0.4.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#rustc-demangle@0.1.24",
          "name": "rustc-demangle",
          "version": "0.1.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/rustc-demangle-0.1.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.217",
          "name": "serde",
          "version": "1.0.217",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.217",
          "name": "serde_derive",
          "version": "1.0.217",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.217"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@1.3.0",
          "name": "shlex",
          "version": "1.3.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-1.3.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar@2.6.0",
          "name": "similar",
          "version": "2.6.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-2.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#similar-asserts@1.6.0",
          "name": "similar-asserts",
          "version": "1.6.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/similar-asserts-1.6.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#stable_deref_trait@1.2.0",
          "name": "stable_deref_trait",
          "version": "1.2.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/stable_deref_trait-1.2.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#symbolic-common@12.16.3",
          "name": "symbolic-common",
          "version": "12.16.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/symbolic-common-12.16.3"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
          "name": "symbolic-demangle",
          "version": "12.16.3",
          "manifest_path": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.96",
          "name": "syn",
          "version": "2.0.96",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.96"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.14",
          "name": "unicode-ident",
          "version": "1.0.14",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.14"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-segmentation@1.12.0",
          "name": "unicode-segmentation",
          "version": "1.12.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-segmentation-1.12.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#uuid@1.11.1",
          "name": "uuid",
          "version": "1.11.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/uuid-1.11.1"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-sys@0.59.0",
          "name": "windows-sys",
          "version": "0.59.0",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-sys-0.59.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows-targets@0.52.6",
          "name": "windows-targets",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows-targets-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_gnullvm@0.52.6",
          "name": "windows_aarch64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_aarch64_msvc@0.52.6",
          "name": "windows_aarch64_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_aarch64_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnu@0.52.6",
          "name": "windows_i686_gnu",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_gnullvm@0.52.6",
          "name": "windows_i686_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_i686_msvc@0.52.6",
          "name": "windows_i686_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_i686_msvc-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnu@0.52.6",
          "name": "windows_x86_64_gnu",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnu-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_gnullvm@0.52.6",
          "name": "windows_x86_64_gnullvm",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_gnullvm-0.52.6"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#windows_x86_64_msvc@0.52.6",
          "name": "windows_x86_64_msvc",
          "version": "0.52.6",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/windows_x86_64_msvc-0.52.6"
        }
      ],
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "exit_code": 0,
      "kind": "exec",
      "pid": 474403,
      "ppid": 473506,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:6571891f52e3536e:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
      "pid": 474403,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:d0467ef2d389a945:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
      "pid": 474403,
      "sha256": "ea7f2554f1b4cd309372a002ade6053e157f7f1622f01c6b74c51110a1dc693b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:70f8f6fef722d902:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
      "pid": 474403,
      "sha256": "e3b553ac54e07e11246124a7befaf0eeb7668b7cfbed742949808375dd6b5f11",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:aa1d2fb22d061ed4:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
      "pid": 474403,
      "sha256": "0a571c2193259c2eeef4d94a385050e9bc3a9ace81785e9932284637fa2856bb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:25bfd95f0fd83bb8:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
      "pid": 474403,
      "sha256": "30705f3dcde6630c6e1ac8fae3da507a2008ecf70b27bc3c3bde708d71289a22",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:c67c164f2d01a433:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
      "pid": 474403,
      "sha256": "ee49c494b141218e666f976656595196367bf5f3953bfe215f8655b5b77976d6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "used:cc:6085563ddc1c4f22:8ab38072045dc3a7:56ebb7935a6ee919",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
      "pid": 474403,
      "sha256": "2cb481fbfc9183493aa4b7d7736c5b040df5956c5011b4ed442bd15307c60794",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
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
      "output": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "cargo_pkg_name": "cpp_demangle",
      "cargo_pkg_version": "0.4.4",
      "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 474403,
      "ppid": 473506,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd",
        "/target/debug/build/cpp_demangle-bdc218a092b7c581",
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
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/rustchzJ5yd/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.build_script_build.2a261d606fc07c65-cgu.4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/cpp_demangle-bdc218a092b7c581",
          "kind": "object",
          "path": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build_script_build-bdc218a092b7c581.1ocoyul6zx1i3r9gkz92nr643.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-474403-1783994556460243519.map",
      "pid": 474403,
      "ppid": 473506,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-474403-1783994556460243519.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "exit_code": 0,
      "kind": "exec",
      "pid": 474495,
      "ppid": 473499,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:fec36c6ac9ebcbbe:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
      "pid": 474495,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:84c812ac47ba682b:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
      "pid": 474495,
      "sha256": "19c425fb8fba4c31176d2695c773b17b98b7431da39bfdd7b1322ecab0df9782",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:cbb1afb8530ae646:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
      "pid": 474495,
      "sha256": "3e3a170f8d462df55f8d77f10b199a8eb935ebf33852321e5ee90a3422b30bad",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:a77d00cac4eaa8d8:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
      "pid": 474495,
      "sha256": "b6f29f5fb9eb205b9b1ac80bbdf9eb3ccb387c5c1e675600e5aad44b4813f047",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:381e15ce3d5f56b1:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
      "pid": 474495,
      "sha256": "11b8f309f2702d788a41c710b99d4fd070b78773b4f72026f29fadc55992ec09",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "used:cc:5588d86099c98adc:2ddab823d039700f:4fc77846b52fff44",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
      "pid": 474495,
      "sha256": "2faf50a7df8593ce0b2519386fd7191478995438688311a3228eed1428d4f9f3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
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
      "output": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.169",
      "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 474495,
      "ppid": 473499,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6",
        "/target/debug/build/libc-08068d25dbed1dac",
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
          "directory": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/rustcC24jX6/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-08068d25dbed1dac",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-08068d25dbed1dac",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-08068d25dbed1dac",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-08068d25dbed1dac",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.build_script_build.122379b8a5e10aba-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-08068d25dbed1dac",
          "kind": "object",
          "path": "/target/debug/build/libc-08068d25dbed1dac/build_script_build-08068d25dbed1dac.9ed0ml1ka0l73fd9nj8lt8byx.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-474495-1783994556641591610.map",
      "pid": 474495,
      "ppid": 473499,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-474495-1783994556641591610.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "exit_code": 0,
      "kind": "exec",
      "pid": 476911,
      "ppid": 476729,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:62cd40011225de4b:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
      "pid": 476911,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:71ca03e4089b7b8e:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "6c644dc45f097b1985fc2486a2514db6bd7d2976d9985e9e29748fd8bbe16767",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:b5c1e687fbcd9c3a:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "9dec8a4a0e61bb2c80b17ff89653dba973f818d722bb7337f1a546427f5fad67",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:7620c878ae7605c0:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "3e364c8bfc27a2900e209f6a3ea5de55ebe9430be4a9e03bba0933429e68e2f6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:f6038f7e212a6970:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "a82f9748b1f68fb5c71d2e770e391729bca37e29c49a2cd37f99a36544783ac4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:300e9f39343ee4ca:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "b95f3c56e36f7cb744b26064b1d973f557d5955c40daab06aa16e87f3990324e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:b4aa5fd9ad3482fd:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "229229247eff52a9f027309dadaa6358e09a543fcaa365b6f5cc53ff806dbb9a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:b264ef76b240393c:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "e323e034922eb359f50ac061cafb261f26608a8b2d28648b2c9beab3d99de6ba",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:246e5025507db594:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "7423ce28af82ee4172f9a7fc69b334184cc0f38f61725733a9f6385d42dbeaa9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:9c41dbab8b7b5b03:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "435dde7fea076eb718ebf0b271d1b37705124878c779eb6c9215a187132eba92",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:d748bd0a5f43462c:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "1525777c4027bc55aa9f9e1a0625359adf58e9edc30f0b9d125bc44f9a548153",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:d14f2380e73f9a96:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "46fc4cef204a339e8b0ca79f03182e12824285f3c4e3d653c99f8428231ef5e2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "used:cc:a5e35b52292e6c2a:9e0d7d7499fffbab:25d7c0844c10b0e7",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
      "pid": 476911,
      "sha256": "d054befa8afa240f9a85cbe1e3407054b07fa8c97a852713cc485a77c2ebf83a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
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
      "output": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "cargo_pkg_name": "symbolic-demangle",
      "cargo_pkg_version": "12.16.3",
      "context_path": "/tmp/native-trace-469897-1783994549460/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-469897-1783994549460/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 476911,
      "ppid": 476729,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libcc-fd91788fd2123bd2.rlib",
        "/target/debug/deps/libshlex-9d2fae39757f538b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
        "/target/debug/build/symbolic-demangle-adec670d1917b46e",
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
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/rustc6Oqcmr/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.1joujy67ub7bdiy4o30hssq34.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.268bud5n1jz317bklhmcryme1.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.3py0muak4lotoaidle9is3xwz.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.4995a3y4xpsttcl1a6vlb3zll.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.5kd5hbqnbcihdi7ke4y566us1.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6gh87urt2ds0if308cpzfe7nt.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.6p4ylb5n38a7ij6fmggl7qncv.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.76m414ckhj5gf22klmswm7490.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.a4h3gbbis4bhvtfkwsirirnbw.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.catchliz7b9t1g11o8nbzhxp7.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.dpcuqrasdzxnx3zp5o35bhre2.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/symbolic-demangle-adec670d1917b46e",
          "kind": "object",
          "path": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build_script_build-adec670d1917b46e.bjey9q9jwsdaz9i3hpfghv6tc.1wtb689.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.10.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.11.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.12.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.13.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.14.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libcc-fd91788fd2123bd2.rlib(cc-fd91788fd2123bd2.cc.703d71f07d825a04-cgu.15.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libshlex-9d2fae39757f538b.rlib(shlex-9d2fae39757f538b.shlex.1ceebad2f47cb4e6-cgu.0.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-476911-1783994562657606467.map",
      "pid": 476911,
      "ppid": 476729,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-476911-1783994562657606467.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
      "parsed_event_count": 4227,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 4229,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "nu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_header.c -o rdkafka_header.o\n38.289  cc1              487868 487865   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_header.d -MP -MQ rdkafka_header.o rdkafka_header.c -quiet -dumpbase rdkafka_header.c -dumpbase-ext ...\n38.330  as               487869 487726   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o tinycthread_extra.o /tmp/ccxP8qfM.s\n38.349  rustc            487871 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n38.350  cc1              487866 487863   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -dumpbase-ext ...\n38.387  cc               487877 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdstring.c -o rdstring.o\n38.393  cc               487879 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_event.c -o rdkafka_event.o\n38.393  cc               487880 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n38.396  cc               487878 487877   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdstring.c -o rdstring.o\n38.398  cc               487881 487880   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n38.409  cc               487883 487879   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_event.c -o rdkafka_event.o\n38.411  cc1              487882 487878   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdstring.d -MP -MQ rdstring.o rdstring.c -quiet -dumpbase rdstring.c -mtune=generic ...\n38.416  cc1              487884 487881   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_admin.d -MP -MQ rdkafka_admin.o rdkafka_admin.c -quiet -dumpbase rdkafka_admin.c -dumpbase-ext ...\n38.418  cc1              487885 487883   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_event.d -MP -MQ rdkafka_event.o rdkafka_event.c -quiet -dumpbase rdkafka_event.c -mtune=generic ...\n38.465  cc               487887 483668   0 /tmp/native-trace-469541-1783994548054/shims/cc -Wl,--version-script=/target/debug/deps/rustcy3HUg3/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcy3HUg3/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n38.465  as               487893 487836   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdports.o /tmp/ccrb1vA5.s\n38.471  cc               487895 487887   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcy3HUg3/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcy3HUg3/symbols.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.00.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.01.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.02.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.03.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.04.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.05.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.06.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.07.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.08.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.09.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.10.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.11.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.12.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.13.rcgu.o /target/debug/deps/serde_derive-667027a283d600f1.serde_derive.76aaea4664c94c20-cgu.14.rcgu.o ...\n38.482  collect2         487897 487895   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcy3HUg3/raw-dylibs ...\n38.491  as               487898 487737   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdregex.o /tmp/ccEDBZ2x.s\n38.498  ld.lld           487899 487897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcy3HUg3/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n38.507  rust-lld         487899 487897   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccjVvidv.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libserde_derive-667027a283d600f1.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n38.529  cc               487901 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n38.540  cc               487903 487901   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n38.546  cc1              487904 487903   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl_plain.d -MP -MQ rdkafka_sasl_plain.o rdkafka_sasl_plain.c -quiet -dumpbase rdkafka_sasl_plain.c -mtune=generic ...\n38.564  cc               487905 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n38.569  cc               487906 487905   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n38.588  cc1              487909 487906   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_interceptor.d -MP -MQ rdkafka_interceptor.o rdkafka_interceptor.c -quiet -dumpbase rdkafka_interceptor.c -mtune=generic ...\n38.606  as               487907 485675   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_msg.o /tmp/ccnOb9aD.s\n38.683  as               487926 487423   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdstring.o /tmp/ccaR5VqO.s\n38.733  cross            487927 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n38.734  rustc            487930 487927   0 /home/xmoe/.cargo/bin/rustc --print target-list\n38.744  as               487928 487689   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_sasl_plain.o /tmp/cccjLDEl.s\n38.746  cc               487940 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n38.748  rustc            487930 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n38.760  cc               487941 487940   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n38.782  cc1              487945 487941   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_writer.d -MP -MQ rdkafka_msgset_writer.o rdkafka_msgset_writer.c -quiet -dumpbase rdkafka_msgset_writer.c -mtune=generic ...\n38.807  rustc            487946 487927   0 /home/xmoe/.cargo/bin/rustc -vV\n38.820  cc               487955 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n38.831  cc               487956 487955   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n38.844  as               487957 487850   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdavl.o /tmp/ccCprUl9.s\n38.847  cc1              487958 487956   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_aux.d -MP -MQ rdkafka_aux.o rdkafka_aux.c -quiet -dumpbase rdkafka_aux.c -dumpbase-ext ...\n38.863  rustc            487946 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.878  cargo            487963 487927   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n38.886  cc               487962 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n38.888  cargo            487963 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n38.889  cc               487972 487962   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n38.906  rustc            487975 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n38.909  as               487973 487645   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdavl.o /tmp/ccLvb3Xd.s\n38.909  cc1              487974 487972   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -mtune=generic ...\n38.921  as               487976 487848   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdlog.o /tmp/cccqDhrX.s\n38.921  rustc            487978 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n38.933  cc               487982 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_background.c -o rdkafka_background.o\n38.935  cc               487980 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata.c -o rdkafka_metadata.o\n38.939  cc               487988 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdregex.c -o rdregex.o\n38.941  rustc            487989 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n38.947  cc               487990 487988   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdregex.c -o rdregex.o\n38.953  cc1              487991 487990   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdregex.d -MP -MQ rdregex.o rdregex.c -quiet -dumpbase rdregex.c -mtune=generic ...\n38.962  cc               487987 487980   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata.c -o rdkafka_metadata.o\n38.973  as               487981 487464   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdlist.o /tmp/ccETVgbU.s\n38.983  cc1              487996 487987   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_metadata.d -MP -MQ rdkafka_metadata.o rdkafka_metadata.c -quiet -dumpbase rdkafka_metadata.c -mtune=generic ...\n38.984  cc               487986 487982   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_background.c -o rdkafka_background.o\n39.003  cc1              487998 487986   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_background.d -MP -MQ rdkafka_background.o rdkafka_background.c -quiet -dumpbase rdkafka_background.c -dumpbase-ext ...\n39.006  sh               487999 2147557   0 /bin/sh -c which ps\n39.007  which            487999 2147557   0 /usr/bin/which ps\n39.012  sh               488000 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.016  ps               488000 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n39.047  cc               488001 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdports.c -o rdports.o\n39.054  cc               488002 488001   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdports.c -o rdports.o\n39.070  cc1              488003 488002   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdports.d -MP -MQ rdports.o rdports.c -quiet -dumpbase rdports.c -mtune=generic ...\n39.073  sh               488005 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n39.075  cpuUsage.sh      488005 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n39.078  sed              488006 488005   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n39.083  cat              488007 488005   0 /usr/bin/cat /proc/2240539/stat\n39.085  cat              488008 488005   0 /usr/bin/cat /proc/4193716/stat\n39.087  sleep            488009 488005   0 /usr/bin/sleep 1\n39.098  rustc            488011 487963   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.107  cross            488013 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n39.108  rustc            488017 488013   0 /home/xmoe/.cargo/bin/rustc --print target-list\n39.118  rustc            488017 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n39.118  rustc            488012 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name serde --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive\" --cfg feature=\"serde_derive\" ...\n39.132  as               488027 485696   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_op.o /tmp/cckzzcEf.s\n39.140  rustc            488031 488013   0 /home/xmoe/.cargo/bin/rustc -vV\n39.145  rustc            488040 487927   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n39.157  rustc            488031 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.157  rustc            488040 487927   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n39.160  cargo            488050 488013   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n39.172  docker           488063 487927   0 /usr/bin/docker --help\n39.197  docker           488075 487927   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n39.210  as               488074 485695   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_queue.o /tmp/ccPeMOpd.s\n39.218  as               488082 487681   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_sasl.o /tmp/cc3GpIbd.s\n39.221  runc             488086 1599     0 /usr/bin/runc --version\n39.228  docker-init      488091 1599     0 /usr/bin/docker-init --version\n39.230  docker           488092 487927   0 \n39.257  runc             488102 1599     0 \n39.263  docker-init      488107 1599     0 /usr/bin/docker-init --version\n39.267  as               488098 487990   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdregex.o /tmp/ccfp2JrK.s\n39.290  as               488108 487878   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdstring.o /tmp/ccduePlg.s\n39.301  rustup           488109 487927   0 \n39.303  cargo            488050 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n39.320  rustc            488118 488050   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.328  as               488119 487903   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_sasl_plain.o /tmp/ccCtG7f9.s\n39.340  rustc            488122 488050   0 \n39.340  as               488120 487691   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_interceptor.o /tmp/ccVXuDp1.s\n39.352  rustc            488128 488050   0 \n39.352  cc               488127 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_header.c -o rdkafka_header.o\n39.363  cc               488126 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata_cache.c -o rdkafka_metadata_cache.o\n39.363  cc               488129 488127   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_header.c -o rdkafka_header.o\n39.371  cc               488133 488126   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_metadata_cache.c -o rdkafka_metadata_cache.o\n39.408  cc1              488147 488146   0 \n39.409  cc               488149 488148   0 \n39.409  cc               488146 488136   0 \n39.409  cc               488148 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl.c -o rdkafka_sasl.o\n39.409  cc1              488135 488133   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_metadata_cache.d -MP -MQ rdkafka_metadata_cache.o rdkafka_metadata_cache.c -quiet -dumpbase rdkafka_metadata_cache.c -mtune=generic ...\n39.409  cc               488136 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdavl.c -o rdavl.o\n39.409  rustup           488137 487927   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n39.412  cc1              488150 488149   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl.d -MP -MQ rdkafka_sasl.o rdkafka_sasl.c -quiet -dumpbase rdkafka_sasl.c -mtune=generic ...\n39.417  cc1              488153 488129   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_header.d -MP -MQ rdkafka_header.o rdkafka_header.c -quiet -dumpbase rdkafka_header.c -mtune=generic ...\n39.429  rustup           488156 487927   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n39.430  rustc            488155 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_executor --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.469  rustc            488169 488050   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n39.477  uname            488170 487927   0 /usr/bin/uname -r\n39.505  rustc            488172 488013   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n39.508  docker           488173 487927   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n39.513  rustc            488172 488013   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n39.531  docker           488194 488013   0 /usr/bin/docker --help\n39.559  cc               488208 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n39.567  rustc            488207 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.602  cc               488212 488208   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_sasl_plain.c -o rdkafka_sasl_plain.o\n39.602  cc1              488213 488212   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_sasl_plain.d -MP -MQ rdkafka_sasl_plain.o rdkafka_sasl_plain.c -quiet -dumpbase rdkafka_sasl_plain.c -mtune=generic ...\n39.603  docker           488214 488013   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n39.614  rustc            488226 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna_adapter --edition=2024 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna_adapter-1.2.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"compiled_data\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiled_data\")) ...\n39.638  as               488232 486600   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_assignor.o /tmp/ccaXopuD.s\n39.639  runc             488236 1599     0 /usr/bin/runc --version\n39.648  systemd-sysctl   488245 488237   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethbf04044 --prefix=/net/ipv4/neigh/vethbf04044 --prefix=/net/ipv6/conf/vethbf04044 --prefix=/net/ipv6/neigh/vethbf04044\n39.648  docker-init      488246 1599     0 /usr/bin/docker-init --version\n39.653  docker           488248 488013   0 /usr/bin/docker info -f {{.SecurityOptions}}\n39.653  systemd-sysctl   488244 488235   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth59b42ee --prefix=/net/ipv4/neigh/veth59b42ee --prefix=/net/ipv6/conf/veth59b42ee --prefix=/net/ipv6/neigh/veth59b42ee\n39.658  cc               488247 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_idempotence.c -o rdkafka_idempotence.o\n39.671  cc               488254 488247   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_idempotence.c -o rdkafka_idempotence.o\n39.671  cc1              488256 488254   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_idempotence.d -MP -MQ rdkafka_idempotence.o rdkafka_idempotence.c -quiet -dumpbase rdkafka_idempotence.c -dumpbase-ext ...\n39.681  runc             488264 1599     0 /usr/bin/runc --version\n39.684  containerd-shim  488266 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 start\n39.692  docker-init      488282 1599     0 /usr/bin/docker-init --version\n39.692  containerd-shim  488283 488266   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 -address /var/run/docker/containerd/containerd.sock\n39.692  as               488265 488129   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_header.o /tmp/ccXIDyYd.s\n39.694  rustc            488263 469960   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name idna --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/idna-1.1.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"compiled_data\" --cfg feature=\"std\" ...\n39.695  runc             488292 488283   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06\n39.695  as               488280 488002   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdports.o /tmp/ccfdgkfC.s\n39.705  exe              488302 488292   0 /proc/self/exe init\n39.736  rustup           488321 488013   0 \n39.744  rustc            488323 469955   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name icu_provider --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/icu_provider-2.2.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::wildcard_dependencies --warn=clippy::useless_transmute --warn=unused_qualifications --warn=unused_macro_rules --warn=unused_lifetimes --warn=clippy::unnecessary-wraps ...\n39.785  cc               488346 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n39.788  cc               488348 488346   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_admin.c -o rdkafka_admin.o\n39.794  cc1              488356 488348   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_admin.d -MP -MQ rdkafka_admin.o rdkafka_admin.c -quiet -dumpbase rdkafka_admin.c -mtune=generic ...\n39.797  rustup           488362 488013   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n39.833  cc               488371 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n39.839  rustup           488373 488013   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n39.843  cc               488374 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_cert.c -o rdkafka_cert.o\n39.846  cc               488383 488374   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_cert.c -o rdkafka_cert.o\n39.862  cc               488372 488371   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_interceptor.c -o rdkafka_interceptor.o\n39.866  cc               488388 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n39.867  cc               488390 488388   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_writer.c -o rdkafka_msgset_writer.o\n39.874  rustc            488389 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures_executor --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-executor-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n39.876  cc1              488391 488390   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_writer.d -MP -MQ rdkafka_msgset_writer.o rdkafka_msgset_writer.c -quiet -dumpbase rdkafka_msgset_writer.c -mtune=generic ...\n39.910  cc1              488384 488383   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_cert.d -MP -MQ rdkafka_cert.o rdkafka_cert.c -quiet -dumpbase rdkafka_cert.c -dumpbase-ext ...\n39.910  cc1              488394 488372   0 \n39.910  uname            488393 488013   0 /usr/bin/uname -r\n39.910  docker           488399 488013   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n39.950  16               488416 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n39.981  frpc             488416 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n39.989  exe              488418 488292   0 /proc/1599/exe -exec-root=/var/run/docker eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06 d7da31e8f8e1\n39.995  as               488419 485738   0 /usr/bin/as -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include --gdwarf-5 --64 -o rdkafka_assignor.o /tmp/cc8Iog1E.s\n40.044  systemd-sysctl   488435 488310   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth75d7597 --prefix=/net/ipv4/neigh/veth75d7597 --prefix=/net/ipv6/conf/veth75d7597 --prefix=/net/ipv6/neigh/veth75d7597\n40.054  systemd-sysctl   488434 488317   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth01847bb --prefix=/net/ipv4/neigh/veth01847bb --prefix=/net/ipv6/conf/veth01847bb --prefix=/net/ipv6/neigh/veth01847bb\n40.061  containerd-shim  488436 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c start\n40.068  exe              488444 1599     0 /proc/self/exe /var/run/docker/netns/71f8de50bb57 all false\n40.069  containerd-shim  488445 488436   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c -address /var/run/docker/containerd/containerd.sock\n40.085  as               488458 487883   0 /usr/bin/as -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include --64 -o rdkafka_event.o /tmp/ccVpyzmC.s\n40.090  sed              488461 488005   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n40.094  cat              488463 488005   0 /usr/bin/cat /proc/2240539/stat\n40.097  cat              488465 488005   0 /usr/bin/cat /proc/4193716/stat\n40.118  runc             488475 488445   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2b f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c\n40.128  exe              488482 488475   0 /proc/self/exe init\n40.150  as               488484 485405   0 /usr/bin/as -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I /target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include --64 -o rdkafka_assignor.o /tmp/ccT8bkdg.s\n40.155  rustc            488485 469950   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name futures --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/futures-0.3.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unreachable_pub --warn=unexpected_cfgs --warn=single_use_lifetimes --warn=rust_2018_idioms --warn=missing_debug_implementations --check-cfg ...\n40.193  runc             488492 488283   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f6 --log-format json --systemd-cgroup start eaa7a17878506a5e696b072537595658a9ab86e54bdf64feaa85bc572f652c06\n40.204  sh               488405 488283   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n40.207  cargo            488501 488405   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n40.213  cc               488504 485657   0 /tmp/native-trace-473283-1783994554865/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n40.221  cc               488506 488504   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I/target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -c rdkafka_msgset_reader.c -o rdkafka_msgset_reader.o\n40.227  cargo-native-tr  488501 488405   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n40.236  cc               488508 485233   0 /tmp/native-trace-473425-1783994555071/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_txnmgr.c -o rdkafka_txnmgr.o\n40.236  cc1              488507 488506   0 /usr/lib/gcc/x86_64-linux-gnu/9/cc1 -quiet -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -I /target/powerpc64le-unknown-linux-gnu/debug/build/libz-sys-e6e16dc330ba8546/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_msgset_reader.d -MP -MQ rdkafka_msgset_reader.o rdkafka_msgset_reader.c -quiet -dumpbase rdkafka_msgset_reader.c -mtune=generic ...\n40.240  cargo            488509 488501   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n40.244  exe              488510 488475   0 /proc/1599/exe -exec-root=/var/run/docker f5c70abe17ceaeaff5c6a002bca8fb53a3c7b62993c549c1c81cbefbe2bb815c d7da31e8f8e1\n40.253  cc               488512 488508   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I/target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -c rdkafka_txnmgr.c -o rdkafka_txnmgr.o\n40.255  cc               488518 484771   0 /tmp/native-trace-470765-1783994551746/shims/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n40.262  cc               488520 488518   0 /usr/bin/cc -MD -MP -g -O2 -fPIC -Wall -Wsign-compare -Wfloat-equal -Wpointer-arith -Wcast-align -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -I/target/aarch64-unknown-linux-gnu/debug/build/libz-sys-7b8265beaa4e3c77/out/include -c rdkafka_aux.c -o rdkafka_aux.o\n40.262  cc1              488521 488512   0 /usr/lib/gcc/x86_64-linux-gnu/11/cc1 -quiet -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -I /target/riscv64gc-unknown-linux-gnu/debug/build/libz-sys-5dbe00129285c0dd/out/include -imultiarch x86_64-linux-gnu -MD rdkafka_txnmgr.d -MP -MQ rdkafka_txnmgr.o rdkafka_txnmgr.c -quiet -dumpbase rdkafka_txnmgr.c -dumpbase-ext ...\n40.273  rustc            488522 488509   0 \n40.281  cc1              488523 488520   0 \n40.289  exe              488528 1599     0 /proc/self/exe /var/run/docker/netns/c3e6fd3a6f95 all false\n40.292  rustc            488527 488509   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
    },
    {
      "argv": [
        "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 474669,
      "build_script_target_dir": "cpp_demangle-bdc218a092b7c581",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build",
      "pid": 474669,
      "ppid": 473456,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/libc-08068d25dbed1dac/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 474673,
      "build_script_target_dir": "libc-08068d25dbed1dac",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-08068d25dbed1dac/build-script-build",
      "pid": 474673,
      "ppid": 473456,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 474673,
      "build_script_target_dir": "libc-08068d25dbed1dac",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 474674,
      "ppid": 474673,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build",
      "pid": 477218,
      "ppid": 473456,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/6546468493072063648detect_compiler_fami"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477223,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/6546468493072063648detect_compiler_fami",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477224,
      "ppid": 477223,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477232,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "powerpc64le-lin",
      "pid": 477283,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/8442321474154837685detect_compiler_fami",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477284,
      "ppid": 477283,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477286,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-m64",
        "-Wall",
        "-Wextra",
        "-fpermissive",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477288,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "flag_check.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase",
        "flag_check",
        "-O0",
        "-Wall",
        "-Wextra",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477289,
      "ppid": 477288,
      "root_cargo_pid": 473456,
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
        "/tmp/ccI3INcu.o",
        "/tmp/ccZ0OaXr.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 477329,
      "ppid": 477288,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
        "-plugin",
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
        "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
        "-plugin-opt=-fresolution=/tmp/ccwfrzsv.res",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "-plugin-opt=-pass-through=-lc",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "--sysroot=/",
        "--build-id",
        "--eh-frame-hdr",
        "-m",
        "elf64lppc",
        "--hash-style=gnu",
        "--as-needed",
        "-dynamic-linker",
        "/lib64/ld64.so.2",
        "-pie",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "collect2",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
      "pid": 477333,
      "ppid": 477288,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
        "-plugin",
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
        "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
        "-plugin-opt=-fresolution=/tmp/ccwfrzsv.res",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "-plugin-opt=-pass-through=-lc",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "--sysroot=/",
        "--build-id",
        "--eh-frame-hdr",
        "-m",
        "elf64lppc",
        "--hash-style=gnu",
        "--as-needed",
        "-dynamic-linker",
        "/lib64/ld64.so.2",
        "-pie",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "ld",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
      "pid": 477340,
      "ppid": 477333,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-E",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/404301563908866550detect_compiler_famil"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477401,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-E",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/404301563908866550detect_compiler_famil",
        "-msecure-plt",
        "-mcpu=power8",
        "-fasynchronous-unwind-tables",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-fstack-clash-protection"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477402,
      "ppid": 477401,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477404,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-m64",
        "-Wall",
        "-Wextra",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477408,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/flag_check.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "flag_check.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase",
        "flag_check",
        "-O0",
        "-Wall",
        "-Wextra",
        "-Wno-changes-meaning",
        "-ffunction-sections",
        "-fdata-sections",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477410,
      "ppid": 477408,
      "root_cargo_pid": 473456,
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
        "/tmp/ccCDWgFw.o",
        "/tmp/ccrmjzCA.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 477430,
      "ppid": 477408,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
        "-plugin",
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
        "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
        "-plugin-opt=-fresolution=/tmp/ccjQLqWw.res",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "-plugin-opt=-pass-through=-lc",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "--sysroot=/",
        "--build-id",
        "--eh-frame-hdr",
        "-m",
        "elf64lppc",
        "--hash-style=gnu",
        "--as-needed",
        "-dynamic-linker",
        "/lib64/ld64.so.2",
        "-pie",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "collect2",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/collect2",
      "pid": 477435,
      "ppid": 477408,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
        "-plugin",
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/liblto_plugin.so",
        "-plugin-opt=/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/lto-wrapper",
        "-plugin-opt=-fresolution=/tmp/ccjQLqWw.res",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "-plugin-opt=-pass-through=-lc",
        "-plugin-opt=-pass-through=-lgcc_s",
        "-plugin-opt=-pass-through=-lgcc",
        "--sysroot=/",
        "--build-id",
        "--eh-frame-hdr",
        "-m",
        "elf64lppc",
        "--hash-style=gnu",
        "--as-needed",
        "-dynamic-linker",
        "/lib64/ld64.so.2",
        "-pie",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "ld",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/ld",
      "pid": 477438,
      "ppid": 477435,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
        "-c",
        "src/swiftdemangle.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 477514,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "src/swiftdemangle.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "swiftdemangle.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477518,
      "ppid": 477514,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
        "/tmp/ccFJwmdA.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 477796,
      "ppid": 477514,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "powerpc64le-lin",
      "pid": 477822,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/Context.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "Context.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 477823,
      "ppid": 477822,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
        "/tmp/ccDxuV4O.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 478140,
      "ppid": 477822,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
        "-c",
        "vendor/swift/lib/Demangling/CrashReporter.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 478171,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/CrashReporter.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "CrashReporter.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 478173,
      "ppid": 478171,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
        "/tmp/ccxPOi6f.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 478181,
      "ppid": 478171,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
        "-c",
        "vendor/swift/lib/Demangling/Demangler.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 478182,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/Demangler.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "Demangler.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 478183,
      "ppid": 478182,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
        "/tmp/cckP2S13.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 478674,
      "ppid": 478182,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
        "-c",
        "vendor/swift/lib/Demangling/Errors.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 478688,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/Errors.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "Errors.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 478689,
      "ppid": 478688,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
        "/tmp/ccGATXFj.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 478700,
      "ppid": 478688,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "cc1plus",
      "pid": 478706,
      "ppid": 478705,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
        "-c",
        "vendor/swift/lib/Demangling/ManglingUtils.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 478705,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
        "/tmp/ccgV3PiD.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 478846,
      "ppid": 478705,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
        "-c",
        "vendor/swift/lib/Demangling/NodeDumper.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 478850,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/NodeDumper.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "NodeDumper.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 478851,
      "ppid": 478850,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
        "/tmp/ccjD81kA.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 479012,
      "ppid": 478850,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
        "-c",
        "vendor/swift/lib/Demangling/NodePrinter.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 479028,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/NodePrinter.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "NodePrinter.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 479034,
      "ppid": 479028,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
        "/tmp/ccwVHyV0.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 479465,
      "ppid": 479028,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-g++",
        "-O0",
        "-ffunction-sections",
        "-fdata-sections",
        "-fPIC",
        "-gdwarf-4",
        "-fno-omit-frame-pointer",
        "-m64",
        "-std=c++17",
        "-I",
        "vendor/swift/include",
        "-DLLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-DSWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "-fpermissive",
        "-Wno-changes-meaning",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
        "-c",
        "vendor/swift/lib/Demangling/Punycode.cpp"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-g++",
      "pid": 479496,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/Punycode.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "Punycode.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 479497,
      "ppid": 479496,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
        "/tmp/ccUcVN6p.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 479689,
      "ppid": 479496,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "powerpc64le-lin",
      "pid": 479695,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
        "-quiet",
        "-I",
        "vendor/swift/include",
        "-imultiarch",
        "powerpc64le-linux-gnu",
        "-D_GNU_SOURCE",
        "-D",
        "LLVM_DISABLE_ABI_BREAKING_CHECKS_ENFORCING=1",
        "-D",
        "SWIFT_STDLIB_HAS_TYPE_PRINTING=1",
        "vendor/swift/lib/Demangling/Remangler.cpp",
        "-msecure-plt",
        "-quiet",
        "-dumpbase",
        "Remangler.cpp",
        "-m64",
        "-mcpu=power8",
        "-auxbase-strip",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "cc1plus",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1plus",
      "pid": 479700,
      "ppid": 479695,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
        "-I",
        "vendor/swift/include",
        "-a64",
        "-mpower8",
        "-many",
        "-mlittle",
        "-o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o",
        "/tmp/cc05kU0t.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/powerpc64le-linux-gnu/9/../../../../powerpc64le-linux-gnu/bin/as",
      "pid": 480880,
      "ppid": 479695,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "cq",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/0602fb52cb66f316-swiftdemangle.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Context.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-CrashReporter.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Demangler.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Errors.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-ManglingUtils.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodeDumper.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-NodePrinter.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Punycode.o",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/9e67921832b6be5b-Remangler.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 480925,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/powerpc64le-linux-gnu-ar",
        "s",
        "/target/powerpc64le-unknown-linux-gnu/debug/build/symbolic-demangle-d9373e712db8cfaf/out/libswiftdemangle.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 477218,
      "build_script_target_dir": "symbolic-demangle-adec670d1917b46e",
      "comm": "powerpc64le-lin",
      "event": "process_exec",
      "image": "/usr/bin/powerpc64le-linux-gnu-ar",
      "pid": 480933,
      "ppid": 477218,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "cpp_demangle",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "event_id": "bsrun:879fe768e1a13410:93fd464f0aa7863e:716a9c7a798f9e02",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/cpp_demangle-bdc218a092b7c581/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
      "out_dir": "/target/debug/build/cpp_demangle-bdc218a092b7c581/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
      "success": true,
      "target": null,
      "version": "0.4.4",
      "_owner": {
        "crate": "cpp_demangle",
        "version": "0.4.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#cpp_demangle@0.4.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cpp_demangle-0.4.4",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "event_id": "bsrun:506248994e02715a:3c839f80d7aba6f2:55b59efa4ce4e1e3",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-08068d25dbed1dac/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
      "out_dir": "/target/debug/build/libc-08068d25dbed1dac/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
      "success": true,
      "target": null,
      "version": "0.2.169",
      "_owner": {
        "crate": "libc",
        "version": "0.2.169",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.169",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.169",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "symbolic-demangle",
      "cwd": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "event_id": "bsrun:8c5a927913717811:2161d06b284b92cc:e0160276b48fa4ce",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/symbolic-demangle-adec670d1917b46e/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
      "out_dir": "/target/debug/build/symbolic-demangle-adec670d1917b46e/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
      "success": true,
      "target": null,
      "version": "12.16.3",
      "_owner": {
        "crate": "symbolic-demangle",
        "version": "12.16.3",
        "package_id": "path+file:///tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3#symbolic-demangle@12.16.3",
        "manifest_dir": "/tmp/crate-build-ppc64le-vtqmkw26/src/symbolic-demangle-12.16.3",
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
      "build_script_root_pid": 474673,
      "build_script_target_dir": "libc-08068d25dbed1dac",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 474674,
      "ppid": 474673,
      "root_cargo_pid": 473456,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 2012,
    "crate": "symbolic-demangle",
    "version": "12.16.3",
    "crate_id": "41287",
    "version_id": "1735502",
    "downloads": 7119025,
    "cumulative_downloads": 101820644669,
    "cumulative_share_of_global": 0.3806838845294647,
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
