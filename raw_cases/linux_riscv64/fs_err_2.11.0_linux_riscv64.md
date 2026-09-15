# `fs-err` `2.11.0`

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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
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
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
    "/target/debug/build/fs-err-c1fbb06d65bc740b",
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
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-156242-1783993106873827932.map",
  "pid": 156242,
  "ppid": 156216,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-156242-1783993106873827932.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "workspace_root": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0"
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
      "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
      "name": "fs-err",
      "version": "2.11.0",
      "manifest_path": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
      "name": "itoa",
      "version": "1.0.18",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
      "name": "memchr",
      "version": "2.8.3",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
      "name": "proc-macro2",
      "version": "1.0.106",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
      "name": "quote",
      "version": "1.0.46",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
      "name": "serde",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
      "name": "serde_core",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
      "name": "serde_derive",
      "version": "1.0.228",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
      "name": "serde_json",
      "version": "1.0.150",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
      "name": "syn",
      "version": "2.0.118",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
      "name": "unicode-ident",
      "version": "1.0.24",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
      "name": "zmij",
      "version": "1.0.23",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
    }
  ],
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 156242,
  "ppid": 156216,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:0ec0ffbf4970da22:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
  "pid": 156242,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:d875b61a5dd92bf4:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "c14faa636ead99901ef36ce6b1ac8cb592dd5a5b0e2fb62bdcd54b808dac4af2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:780e50aad47a589c:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "bfab8077fa8c5ca0112e9f0fee21bd91218ccfed12b4a1a4903daed15cd4db39",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:6b7d9b3c69dca3ea:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "b4e25f5606fc5bf6bc5b025d44ce0c96a6945a3c18f6a340879487ea1ee9038f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:9ed484f25ccc434e:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "4e596797a3d7a0b9bd32ef9200a3d5a4699b357298a5680c5f856a1135e0b936",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:8aa357b99a3a7bc1:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "ac6d3bd917e5db75ec842931617b0d81c48543deccc48437c1617d55e2527121",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "used:cc:fed3ec773cb0e2ea:f81e004227d5ca64:f34e85808ce22180",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
  "pid": 156242,
  "sha256": "e7ace0b0082d7a8197cba2b15d92f174bb038f7655f21d838d4f97a28d3f8987",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
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
  "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "cargo_pkg_name": "fs-err",
  "cargo_pkg_version": "2.11.0",
  "context_path": "/tmp/native-trace-155882-1783993104292/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-155882-1783993104292/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 156242,
  "ppid": 156216,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
    "/target/debug/build/fs-err-c1fbb06d65bc740b",
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
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
      "kind": "object",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-156242-1783993106873827932.map",
  "pid": 156242,
  "ppid": 156216,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-156242-1783993106873827932.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
  "parse_error_count": 2,
  "parsed_event_count": 807,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 809,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=dd9c2e60ffbfa9be ...\n13.887  rustc            159903 159627   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name borsh --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n13.912  runc             159913 150864   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a --log-format json --systemd-cgroup kill --all 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0 9\n13.932  runc             159919 150864   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a --log-format json --systemd-cgroup delete 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0\n14.031  cc               160025 159897   0 /tmp/native-trace-158948-1783993117459/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcmahJeJ/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0kdd4or.rcgu.o ...\n14.033  cc               160027 160025   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcmahJeJ/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0kdd4or.rcgu.o ...\n14.037  cc               160026 159900   0 /tmp/native-trace-158964-1783993117488/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustczOTMTl/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0adw4co.rcgu.o ...\n14.039  collect2         160028 160027   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.040  cc               160029 160026   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustczOTMTl/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0adw4co.rcgu.o ...\n14.041  ld.lld           160030 160028   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.044  rust-lld         160030 160028   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.047  collect2         160032 160029   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.051  ld.lld           160033 160032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.054  rust-lld         160033 160032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.104  rustc            160069 159639   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=dd9c2e60ffbfa9be ...\n14.156  containerd-shim  160076 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a delete\n14.161  runc             160084 160076   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe --log-format json delete --force 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0\n14.172  build-script-bu  160090 159458   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.179  rustc            160091 160090   0 \n14.190  build-script-bu  160095 159479   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.195  rustc            160097 160095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.202  rustc            160098 159458   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=315ec8ea227b3040 ...\n14.207  systemd-sysctl   160100 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc51a55c --prefix=/net/ipv4/neigh/vethc51a55c --prefix=/net/ipv6/conf/vethc51a55c --prefix=/net/ipv6/neigh/vethc51a55c\n14.224  rustc            160103 159479   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=09cdc21e5e3a7564 ...\n14.297  cc               160174 160069   0 /tmp/native-trace-158684-1783993117222/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcaIoDiv/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.16vl5we.rcgu.o ...\n14.298  cc               160175 160174   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcaIoDiv/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.16vl5we.rcgu.o ...\n14.303  collect2         160176 160175   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccceJpKk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.307  ld.lld           160178 160176   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccceJpKk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.310  rust-lld         160178 160176   0 \n14.408  build-script-bu  160265 159639   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.410  rustc            160264 159217   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n14.411  rustc            160266 160265   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.424  rustc            160272 159639   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5a4db143942ea1f3 ...\n14.499  cc               160328 160264   0 /tmp/native-trace-158814-1783993117322/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcWw97ph/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.149vxrj.rcgu.o ...\n14.500  cc               160329 160328   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcWw97ph/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.149vxrj.rcgu.o ...\n14.503  collect2         160330 160329   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.505  ld.lld           160331 160330   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n14.506  rust-lld         160331 160330   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.576  build-script-bu  160349 159217   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n14.578  aarch64-linux-g  160350 160349   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/12037248445461796857detect_compiler_family.c\n14.579  cc1              160351 160350   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/12037248445461796857detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n14.584  aarch64-linux-g  160352 160349   0 /usr/bin/aarch64-linux-gnu-gcc -?\n14.587  aarch64-linux-g  160353 160349   0 /usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n14.588  cc1              160354 160353   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu liblz4/lib/lz4.c -quiet -dumpbase lz4.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4.o -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n14.799  git              160355 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n15.819  cargo            160356 159617   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.832  rustc            160357 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.852  rustc            160366 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n15.852  rustc            160365 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.853  rustc            160367 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n15.921  rustc            160385 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.982  cc               160395 160367   0 /tmp/native-trace-159617-1783993119995/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcQcPrdV/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.983  cc               160396 160395   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcQcPrdV/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.985  collect2         160397 160396   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.987  ld.lld           160398 160397   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n15.988  rust-lld         160398 160397   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.030  build-script-bu  160416 160356   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n16.032  rustc            160417 160416   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.045  rustc            160421 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.172  cargo            160425 159625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n16.186  rustc            160426 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.208  rustc            160435 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.208  rustc            160433 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n16.208  rustc            160436 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n16.281  rustc            160453 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n16.331  sh               160464 2147557   0 /bin/sh -c which ps\n16.333  which            160464 2147557   0 /usr/bin/which ps\n16.336  sh               160465 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.337  ps               160465 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.345  cc               160466 160435   0 /tmp/native-trace-159625-1783993120020/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcpl3Vkm/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n16.347  cc               160467 160466   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcpl3Vkm/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n16.350  collect2         160468 160467   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.352  ld.lld           160469 160468   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n16.354  rust-lld         160469 160468   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.367  sh               160486 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.368  cpuUsage.sh      160486 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.370  sed              160487 160486   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.373  cat              160488 160486   0 /usr/bin/cat /proc/2240539/stat\n16.375  cat              160489 160486   0 /usr/bin/cat /proc/4193716/stat\n16.377  sleep            160490 160486   0 /usr/bin/sleep 1\n16.406  build-script-bu  160492 160425   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n16.408  rustc            160493 160492   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.423  rustc            160497 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.681  rustc            160523 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n16.762  cc               160558 160523   0 /tmp/native-trace-159617-1783993119995/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcGD5Uco/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0it2po4.rcgu.o ...\n16.763  cc               160559 160558   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcGD5Uco/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0it2po4.rcgu.o ...\n16.767  collect2         160560 160559   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.768  ld.lld           160561 160560   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n16.770  rust-lld         160561 160560   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.842  build-script-bu  160584 160356   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n16.844  powerpc64le-lin  160585 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/2496427531842824230detect_compiler_family.c\n16.845  cc1              160586 160585   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/2496427531842824230detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.851  powerpc64le-lin  160587 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n16.855  powerpc64le-lin  160588 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n16.857  cc1              160590 160588   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu liblz4/lib/lz4.c -msecure-plt -quiet -dumpbase lz4.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/efce31824dbf3730-lz4.o -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections ...\n17.023  rustc            160607 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n17.102  cc               160642 160607   0 /tmp/native-trace-159625-1783993120020/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcB8PYbx/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0qejako.rcgu.o ...\n17.103  cc               160643 160642   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcB8PYbx/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0qejako.rcgu.o ...\n17.106  collect2         160644 160643   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.108  ld.lld           160645 160644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n17.109  rust-lld         160645 160644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.178  build-script-bu  160663 160425   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n17.180  riscv64-linux-g  160664 160663   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/2020685848391566029detect_compiler_family.c\n17.182  cc1              160665 160664   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/2020685848391566029detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 2020685848391566029detect_compiler_family.c -dumpbase-ext .c\n17.188  riscv64-linux-g  160666 160663   0 /usr/bin/riscv64-linux-gnu-gcc -?\n17.192  riscv64-linux-g  160667 160663   0 /usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n17.194  cc1              160668 160667   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu liblz4/lib/lz4.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/ -dumpbase efce31824dbf3730-lz4.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n17.379  sed              160669 160486   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.382  cat              160670 160486   0 /usr/bin/cat /proc/2240539/stat\n17.384  cat              160672 160486   0 /usr/bin/cat /proc/4193716/stat\n17.435  runc             160674 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup kill --all 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea 9\n17.453  runc             160681 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup delete 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n17.460  runc             160687 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup kill --all d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb 9\n17.477  runc             160692 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup delete d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 156298,
  "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build",
  "pid": 156298,
  "ppid": 156136,
  "root_cargo_pid": 156136,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_out_dir": "/target/debug/build/fs-err-c1fbb06d65bc740b/out"
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
  "build_script_root_pid": 156298,
  "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 156299,
  "ppid": 156298,
  "root_cargo_pid": 156136,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_out_dir": "/target/debug/build/fs-err-c1fbb06d65bc740b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_77a383603c224a07_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 156298,
  "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 156301,
  "ppid": 156298,
  "root_cargo_pid": 156136,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_build_script_out_dir": "/target/debug/build/fs-err-c1fbb06d65bc740b/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "crate": "fs-err",
  "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "event_id": "bsrun:ce8e1435cd696241:96725cd455cfc602:2375a7fc4e20169f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
  "out_dir": "/target/debug/build/fs-err-c1fbb06d65bc740b/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
  "success": true,
  "target": null,
  "version": "2.11.0",
  "_owner": {
    "crate": "fs-err",
    "version": "2.11.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
    "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
    "source": "cwd_prefix"
  }
}
```

#### Record 19

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 156298,
  "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 156299,
  "ppid": 156298,
  "root_cargo_pid": 156136,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 20

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_77a383603c224a07_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 156298,
  "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 156301,
  "ppid": 156298,
  "root_cargo_pid": 156136,
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
  "time": "2026-07-14T01:38:44.439430+00:00",
  "crate": "fs-err",
  "version": "2.11.0",
  "architecture": "riscv64",
  "duration_seconds": 25.97913854662329,
  "trace_record_count": 18,
  "trace_owner_summary": {
    "owner_package_count": 13,
    "owner_packages": [
      {
        "crate": "serde_derive",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml"
      },
      {
        "crate": "unicode-ident",
        "version": "1.0.24",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml"
      },
      {
        "crate": "proc-macro2",
        "version": "1.0.106",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml"
      },
      {
        "crate": "serde_core",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml"
      },
      {
        "crate": "serde_json",
        "version": "1.0.150",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "serde",
        "version": "1.0.228",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml"
      },
      {
        "crate": "memchr",
        "version": "2.8.3",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml"
      },
      {
        "crate": "quote",
        "version": "1.0.46",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml"
      },
      {
        "crate": "itoa",
        "version": "1.0.18",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml"
      },
      {
        "crate": "syn",
        "version": "2.0.118",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml"
      },
      {
        "crate": "zmij",
        "version": "1.0.23",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml"
      },
      {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "manifest_path": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "fs-err",
        "version": "2.11.0",
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
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "workspace_root": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0"
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
          "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
          "name": "fs-err",
          "version": "2.11.0",
          "manifest_path": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#itoa@1.0.18",
          "name": "itoa",
          "version": "1.0.18",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/itoa-1.0.18"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#memchr@2.8.3",
          "name": "memchr",
          "version": "2.8.3",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#proc-macro2@1.0.106",
          "name": "proc-macro2",
          "version": "1.0.106",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#quote@1.0.46",
          "name": "quote",
          "version": "1.0.46",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde@1.0.228",
          "name": "serde",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_core@1.0.228",
          "name": "serde_core",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_core-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_derive@1.0.228",
          "name": "serde_derive",
          "version": "1.0.228",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_derive-1.0.228"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#serde_json@1.0.150",
          "name": "serde_json",
          "version": "1.0.150",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/serde_json-1.0.150"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#syn@2.0.118",
          "name": "syn",
          "version": "2.0.118",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#unicode-ident@1.0.24",
          "name": "unicode-ident",
          "version": "1.0.24",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#zmij@1.0.23",
          "name": "zmij",
          "version": "1.0.23",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/zmij-1.0.23"
        }
      ],
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 156242,
      "ppid": 156216,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:0ec0ffbf4970da22:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
      "pid": 156242,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:d875b61a5dd92bf4:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "c14faa636ead99901ef36ce6b1ac8cb592dd5a5b0e2fb62bdcd54b808dac4af2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:780e50aad47a589c:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "bfab8077fa8c5ca0112e9f0fee21bd91218ccfed12b4a1a4903daed15cd4db39",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:6b7d9b3c69dca3ea:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "b4e25f5606fc5bf6bc5b025d44ce0c96a6945a3c18f6a340879487ea1ee9038f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:9ed484f25ccc434e:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "4e596797a3d7a0b9bd32ef9200a3d5a4699b357298a5680c5f856a1135e0b936",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:8aa357b99a3a7bc1:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "ac6d3bd917e5db75ec842931617b0d81c48543deccc48437c1617d55e2527121",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "used:cc:fed3ec773cb0e2ea:f81e004227d5ca64:f34e85808ce22180",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
      "pid": 156242,
      "sha256": "e7ace0b0082d7a8197cba2b15d92f174bb038f7655f21d838d4f97a28d3f8987",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
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
      "output": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "cargo_pkg_name": "fs-err",
      "cargo_pkg_version": "2.11.0",
      "context_path": "/tmp/native-trace-155882-1783993104292/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-155882-1783993104292/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 156242,
      "ppid": 156216,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
        "/target/debug/build/fs-err-c1fbb06d65bc740b",
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
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/rustcwazjfA/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.53aru7al2dyeo7phxdlaw0pm8.1bw26le.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.5cir7ch1bcu0w24imbf8fj1cn.1bw26le.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.98hhqz212arpsxaw0678rwkgc.1bw26le.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.aegxw11tfuce6veom9hx60lww.1bw26le.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.c40ki64k2l4n1j0mizoyfxquv.1bw26le.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/fs-err-c1fbb06d65bc740b",
          "kind": "object",
          "path": "/target/debug/build/fs-err-c1fbb06d65bc740b/build_script_build-c1fbb06d65bc740b.b6sknk69cawbo9da7tmzpdk42.1bw26le.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-156242-1783993106873827932.map",
      "pid": 156242,
      "ppid": 156216,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-156242-1783993106873827932.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
      "parsed_event_count": 807,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 809,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=dd9c2e60ffbfa9be ...\n13.887  rustc            159903 159627   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name borsh --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n13.912  runc             159913 150864   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a --log-format json --systemd-cgroup kill --all 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0 9\n13.932  runc             159919 150864   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a --log-format json --systemd-cgroup delete 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0\n14.031  cc               160025 159897   0 /tmp/native-trace-158948-1783993117459/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcmahJeJ/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0kdd4or.rcgu.o ...\n14.033  cc               160027 160025   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcmahJeJ/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0kdd4or.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0kdd4or.rcgu.o ...\n14.037  cc               160026 159900   0 /tmp/native-trace-158964-1783993117488/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustczOTMTl/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0adw4co.rcgu.o ...\n14.039  collect2         160028 160027   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.040  cc               160029 160026   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustczOTMTl/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.0adw4co.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.0adw4co.rcgu.o ...\n14.041  ld.lld           160030 160028   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.044  rust-lld         160030 160028   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccormw9I.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.047  collect2         160032 160029   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.051  ld.lld           160033 160032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.054  rust-lld         160033 160032   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccMeNWLR.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.104  rustc            160069 159639   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=dd9c2e60ffbfa9be ...\n14.156  containerd-shim  160076 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a delete\n14.161  runc             160084 160076   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe --log-format json delete --force 06cc4614851fad9dcfc54cdc6e5dd672f7d16dfaabdad9220430a9e100a3bfe0\n14.172  build-script-bu  160090 159458   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.179  rustc            160091 160090   0 \n14.190  build-script-bu  160095 159479   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.195  rustc            160097 160095   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.202  rustc            160098 159458   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=315ec8ea227b3040 ...\n14.207  systemd-sysctl   160100 156805   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc51a55c --prefix=/net/ipv4/neigh/vethc51a55c --prefix=/net/ipv6/conf/vethc51a55c --prefix=/net/ipv6/neigh/vethc51a55c\n14.224  rustc            160103 159479   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=09cdc21e5e3a7564 ...\n14.297  cc               160174 160069   0 /tmp/native-trace-158684-1783993117222/shims/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcaIoDiv/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.16vl5we.rcgu.o ...\n14.298  cc               160175 160174   0 /usr/bin/cc -m64 /target/debug/build/crc32c-b16b7cddb784a8a8/rustcaIoDiv/symbols.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.075vazkgjd6kosfjxga48viiq.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.083bj5dxhmk6xke8r936ta7x8.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.0hy2ade6gcjsdf36hdj71f1oi.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1m03vp7r0r3cqn2fkumjq6nvk.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.1un56sa4czs2ba7zu42jo7tt6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.25885w9ll3c1wxcmqzx5lgvt3.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2lap3bpr0i8ovkgm3x24qp9ju.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.2w02op50nfsuo0xm4agz2esck.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.344wrlqoq64nmaimonvpo6s9t.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.34dn65qd6exbpokvv6j2f21ha.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.35a01tixlj7ozl5giltj8o5t6.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3ca2hhikudd6gg6lgdzacy0ai.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3cupjjfnxoknvlbq9emj17u7n.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3eh7fc5r6hzm327gz02zlcs1v.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3g3e82dx49ewgc6dxc3qrd947.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3kgmr9s9ed4tes1znrdioyiio.16vl5we.rcgu.o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8.3yoxnyepyor2vhyzyy7dozw9j.16vl5we.rcgu.o ...\n14.303  collect2         160176 160175   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccceJpKk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.307  ld.lld           160178 160176   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccceJpKk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crc32c-b16b7cddb784a8a8/build_script_build-b16b7cddb784a8a8 ...\n14.310  rust-lld         160178 160176   0 \n14.408  build-script-bu  160265 159639   0 /target/debug/build/crc32c-b16b7cddb784a8a8/build-script-build\n14.410  rustc            160264 159217   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n14.411  rustc            160266 160265   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.424  rustc            160272 159639   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crc32c --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=5a4db143942ea1f3 ...\n14.499  cc               160328 160264   0 /tmp/native-trace-158814-1783993117322/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcWw97ph/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.149vxrj.rcgu.o ...\n14.500  cc               160329 160328   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcWw97ph/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.149vxrj.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.149vxrj.rcgu.o ...\n14.503  collect2         160330 160329   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.505  ld.lld           160331 160330   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n14.506  rust-lld         160331 160330   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccADLzew.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.576  build-script-bu  160349 159217   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n14.578  aarch64-linux-g  160350 160349   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/12037248445461796857detect_compiler_family.c\n14.579  cc1              160351 160350   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/12037248445461796857detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n14.584  aarch64-linux-g  160352 160349   0 /usr/bin/aarch64-linux-gnu-gcc -?\n14.587  aarch64-linux-g  160353 160349   0 /usr/bin/aarch64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -Wall -Wextra -o /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n14.588  cc1              160354 160353   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu liblz4/lib/lz4.c -quiet -dumpbase lz4.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/lz4-sys-9327eaa96e0dea45/out/efce31824dbf3730-lz4.o -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections -fPIC ...\n14.799  git              160355 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n15.819  cargo            160356 159617   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target powerpc64le-unknown-linux-gnu\n15.832  rustc            160357 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.852  rustc            160366 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n15.852  rustc            160365 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.853  rustc            160367 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n15.921  rustc            160385 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n15.982  cc               160395 160367   0 /tmp/native-trace-159617-1783993119995/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcQcPrdV/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.983  cc               160396 160395   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcQcPrdV/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n15.985  collect2         160397 160396   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.987  ld.lld           160398 160397   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n15.988  rust-lld         160398 160397   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccJJ7kSz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.030  build-script-bu  160416 160356   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n16.032  rustc            160417 160416   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.045  rustc            160421 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.172  cargo            160425 159625   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n16.186  rustc            160426 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.208  rustc            160435 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.208  rustc            160433 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n16.208  rustc            160436 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n16.281  rustc            160453 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n16.331  sh               160464 2147557   0 /bin/sh -c which ps\n16.333  which            160464 2147557   0 /usr/bin/which ps\n16.336  sh               160465 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.337  ps               160465 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n16.345  cc               160466 160435   0 /tmp/native-trace-159625-1783993120020/shims/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcpl3Vkm/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n16.347  cc               160467 160466   0 /usr/bin/cc -m64 /target/debug/build/libc-8a22300c8f78b6db/rustcpl3Vkm/symbols.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.0.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.1.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.2.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.build_script_build.937d95d0202f1112-cgu.3.rcgu.o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db.ae2u0rm7cnv1vb69v9tx4k9kc.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de ...\n16.350  collect2         160468 160467   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.352  ld.lld           160469 160468   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/libc-8a22300c8f78b6db/build_script_build-8a22300c8f78b6db ...\n16.354  rust-lld         160469 160468   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9aGjZM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.367  sh               160486 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n16.368  cpuUsage.sh      160486 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n16.370  sed              160487 160486   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n16.373  cat              160488 160486   0 /usr/bin/cat /proc/2240539/stat\n16.375  cat              160489 160486   0 /usr/bin/cat /proc/4193716/stat\n16.377  sleep            160490 160486   0 /usr/bin/sleep 1\n16.406  build-script-bu  160492 160425   0 /target/debug/build/libc-8a22300c8f78b6db/build-script-build\n16.408  rustc            160493 160492   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n16.423  rustc            160497 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name libc --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=clippy::used_underscore_binding --allow=unused_qualifications --warn=clippy::unnecessary_semicolon --allow=clippy::unnecessary_cast --allow=clippy::uninlined_format_args --warn=clippy::ptr_as_ptr ...\n16.681  rustc            160523 160356   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n16.762  cc               160558 160523   0 /tmp/native-trace-159617-1783993119995/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcGD5Uco/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0it2po4.rcgu.o ...\n16.763  cc               160559 160558   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcGD5Uco/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0it2po4.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0it2po4.rcgu.o ...\n16.767  collect2         160560 160559   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.768  ld.lld           160561 160560   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n16.770  rust-lld         160561 160560   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cchtCTOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.842  build-script-bu  160584 160356   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n16.844  powerpc64le-lin  160585 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -E /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/2496427531842824230detect_compiler_family.c\n16.845  cc1              160586 160585   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -E -quiet -imultiarch powerpc64le-linux-gnu /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/2496427531842824230detect_compiler_family.c -msecure-plt -mcpu=power8 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.851  powerpc64le-lin  160587 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -?\n16.855  powerpc64le-lin  160588 160584   0 /usr/bin/powerpc64le-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -m64 -Wall -Wextra -o /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n16.857  cc1              160590 160588   0 /usr/lib/gcc-cross/powerpc64le-linux-gnu/9/cc1 -quiet -imultiarch powerpc64le-linux-gnu liblz4/lib/lz4.c -msecure-plt -quiet -dumpbase lz4.c -m64 -mcpu=power8 -auxbase-strip /target/powerpc64le-unknown-linux-gnu/debug/build/lz4-sys-18684ad79a9c35ae/out/efce31824dbf3730-lz4.o -g -gdwarf-4 -O3 -Wall -Wextra -ffunction-sections -fdata-sections ...\n17.023  rustc            160607 160425   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2015 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=001fb5c653d2c8bb ...\n17.102  cc               160642 160607   0 /tmp/native-trace-159625-1783993120020/shims/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcB8PYbx/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0qejako.rcgu.o ...\n17.103  cc               160643 160642   0 /usr/bin/cc -m64 /target/debug/build/lz4-sys-c23488cb26154d2e/rustcB8PYbx/symbols.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.1x8ogoz67jp9f7cnhh5imfxb3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2gq86ucysro3qa7ajjctl69de.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.2zrr395ryhjjgh2zh4447aaog.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.33k02gkrp6ktsndc8dr97fwlj.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3idjh7i4qentj8sxfqoopszkb.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.3qs7jww1arkc2j6cnscp9ne8g.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.47bcohzutb454rl1v2sct9ky7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.4nau6vah1z8b8d4a9eqeqtt75.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.5w51yp386zx6zvpya9qg3ay90.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.7tyhkq2ynf1qrzjt32tw6ofmg.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.80zus7xf1tix61pvdcwjqcxq7.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.9805db7ioqhqpjrw88ha5326e.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.991tg3gq5u8n14h6wmwkffyxc.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a2i3bk118epfwokuaxisyz13h.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.a7qgmcqx83o8pyyi3t23sh0k3.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.ai80irtuarg1m1ahop22btden.0qejako.rcgu.o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e.akffp5v49qb0cmgshzja6y9qh.0qejako.rcgu.o ...\n17.106  collect2         160644 160643   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.108  ld.lld           160645 160644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lz4-sys-c23488cb26154d2e/build_script_build-c23488cb26154d2e ...\n17.109  rust-lld         160645 160644   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccoJSuyI.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.178  build-script-bu  160663 160425   0 /target/debug/build/lz4-sys-c23488cb26154d2e/build-script-build\n17.180  riscv64-linux-g  160664 160663   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/2020685848391566029detect_compiler_family.c\n17.182  cc1              160665 160664   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/2020685848391566029detect_compiler_family.c -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 2020685848391566029detect_compiler_family.c -dumpbase-ext .c\n17.188  riscv64-linux-g  160666 160663   0 /usr/bin/riscv64-linux-gnu-gcc -?\n17.192  riscv64-linux-g  160667 160663   0 /usr/bin/riscv64-linux-gnu-gcc -O3 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -Wall -Wextra -o /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/efce31824dbf3730-lz4.o -c liblz4/lib/lz4.c\n17.194  cc1              160668 160667   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu liblz4/lib/lz4.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/lz4-sys-523adbfd84aa8ec0/out/ -dumpbase efce31824dbf3730-lz4.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -g -gdwarf-4 ...\n17.379  sed              160669 160486   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n17.382  cat              160670 160486   0 /usr/bin/cat /proc/2240539/stat\n17.384  cat              160672 160486   0 /usr/bin/cat /proc/4193716/stat\n17.435  runc             160674 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup kill --all 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea 9\n17.453  runc             160681 155839   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285d --log-format json --systemd-cgroup delete 204aa8809be2eff118d11d642560181d5ff836c36206c05d2b53cd9285de9eea\n17.460  runc             160687 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup kill --all d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb 9\n17.477  runc             160692 155832   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc925 --log-format json --systemd-cgroup delete d85240e6f88498dd4d5f5c8fed035725b1f280c2797af9c57f767ecc9250aadb\n"
    },
    {
      "argv": [
        "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 156298,
      "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build",
      "pid": 156298,
      "ppid": 156136,
      "root_cargo_pid": 156136,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 156298,
      "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 156299,
      "ppid": 156298,
      "root_cargo_pid": 156136,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_77a383603c224a07_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 156298,
      "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 156301,
      "ppid": 156298,
      "root_cargo_pid": 156136,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "fs-err",
      "cwd": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "event_id": "bsrun:ce8e1435cd696241:96725cd455cfc602:2375a7fc4e20169f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/fs-err-c1fbb06d65bc740b/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
      "out_dir": "/target/debug/build/fs-err-c1fbb06d65bc740b/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
      "success": true,
      "target": null,
      "version": "2.11.0",
      "_owner": {
        "crate": "fs-err",
        "version": "2.11.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0#fs-err@2.11.0",
        "manifest_dir": "/tmp/crate-build-riscv64-1izf_yn_/src/fs-err-2.11.0",
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
      "build_script_root_pid": 156298,
      "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 156299,
      "ppid": 156298,
      "root_cargo_pid": 156136,
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
        "autocfg_77a383603c224a07_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/fs-err-d223f2b3d73c7254/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 156298,
      "build_script_target_dir": "fs-err-c1fbb06d65bc740b",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 156301,
      "ppid": 156298,
      "root_cargo_pid": 156136,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 739,
    "crate": "fs-err",
    "version": "2.11.0",
    "crate_id": "204330",
    "version_id": "961716",
    "downloads": 36273368,
    "cumulative_downloads": 82180564333,
    "cumulative_share_of_global": 0.30725415817991675,
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
