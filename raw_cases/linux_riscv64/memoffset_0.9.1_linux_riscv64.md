# `memoffset` `0.9.1`

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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
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
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
    "/target/debug/build/memoffset-e7952ae2e0ab5922",
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
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-35587-1783992729178548797.map",
  "pid": 35587,
  "ppid": 35446,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-35587-1783992729178548797.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "workspace_root": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1"
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
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.4",
      "name": "doc-comment",
      "version": "0.3.4",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
      "name": "memoffset",
      "version": "0.9.1",
      "manifest_path": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1"
    }
  ],
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "exit_code": 0,
  "kind": "exec",
  "pid": 35587,
  "ppid": 35446,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:88c3273c7fed5c05:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
  "pid": 35587,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:2393373accbce763:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "5d577609ab01f59f82fd740ce11751156fbc52d16ca32e42e43b19f7c714ca3b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:109f0d0e6671dc05:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "7e36a3b9e005c511258788aa39cda071ef2932fcc34cec821316994a7749ee71",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:3ef2518c9e2caf40:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "e4034be838191d0d1e908d05794d859ab4bf3f3dc9dc41d0f013d48a133fe9e5",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:183b5baf9f03489c:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "8a066690afeaf612b53a771ba567e08f512351055e0db29e459db4d4886b63e3",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:0d0631077d4b1c7d:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "feea08b5110ffdb06e842907cf6971021f88da145841dc062cf4494cfb751007",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:83664ffcf266a7e2:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "1f908486d5288d26a226bba02d00536ac3427ae636d02b4904955e5d39890bde",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "used:cc:be7be0f00f695509:5e4afd5e3326021c:bfdb02a4b52dd2ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
  "pid": 35587,
  "sha256": "4120d7db7a1883e24ca0b5e64ac37d1fc169bf9f861a115dd2e48b95d15ab0bf",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
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
  "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "cargo_pkg_name": "memoffset",
  "cargo_pkg_version": "0.9.1",
  "context_path": "/tmp/native-trace-34378-1783992725358/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-34378-1783992725358/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 35587,
  "ppid": 35446,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
    "/target/debug/build/memoffset-e7952ae2e0ab5922",
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
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
      "kind": "object",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-35587-1783992729178548797.map",
  "pid": 35587,
  "ppid": 35446,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-35587-1783992729178548797.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
    "source": "cargo_manifest_dir"
  }
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

#### Record 15

```json
{
  "argv": [
    "/usr/local/bin/execsnoop",
    "-t"
  ],
  "event": "process_tracer_diagnostic",
  "exit_status": null,
  "parse_error_count": 1,
  "parsed_event_count": 531,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 532,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "utable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.580   rustc            37327  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.608   cc               37351  37326    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.610   cc               37356  37351    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.613   collect2         37357  37356    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.615   ld.lld           37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n4.617   rust-lld         37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.650   cc               37380  37325    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.651   cc               37381  37327    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.651   cc               37382  37380    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.652   cc               37383  37381    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.655   collect2         37385  37382    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.656   collect2         37386  37383    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.658   ld.lld           37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n4.658   ld.lld           37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n4.660   rust-lld         37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.661   rust-lld         37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.673   build-script-bu  37393  37290    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n4.684   cc               37423  37321    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.686   cc               37424  37423    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.690   collect2         37425  37424    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.692   ld.lld           37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n4.695   rust-lld         37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.708   build-script-bu  37444  37290    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n4.711   build-script-bu  37446  37290    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n4.726   cargo            37447  36863    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n4.737   build-script-bu  37449  37290    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n4.741   rustc            37450  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n4.743   rustc            37452  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.769   rustc            37465  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.769   rustc            37464  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.771   rustc            37466  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.771   rustc            37467  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=cbc0344642a3fe61 ...\n4.801   cc               37488  37467    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.802   cc               37493  37488    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.806   collect2         37494  37493    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.807   ld.lld           37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n4.809   rust-lld         37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.843   cc               37518  37464    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.844   cc               37519  37466    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.847   cc               37521  37519    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.847   cc               37520  37518    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.848   collect2         37525  37521    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.851   ld.lld           37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n4.851   collect2         37527  37520    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.854   rustc            37526  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.854   ld.lld           37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n4.856   rust-lld         37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.857   rust-lld         37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.863   build-script-bu  37531  37447    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n4.876   cc               37568  37465    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.877   cc               37570  37568    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.881   collect2         37571  37570    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.884   ld.lld           37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n4.886   rust-lld         37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.911   build-script-bu  37590  37447    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n4.915   build-script-bu  37592  37447    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n4.927   build-script-bu  37594  37447    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n4.933   rustc            37596  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.995   rustc            37606  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.997   rustc            37607  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.081   rustc            37621  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=2bb0f49e2ccb2b73 ...\n5.117   rustc            37628  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.141   rustc            37636  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.202   rustc            37646  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c73793a7c0eb3dd6 ...\n5.266   rustc            37653  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.344   rustc            37661  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c16cb3cec9db833d ...\n7.879   sh               38036  2147557   0 /bin/sh -c which ps\n7.880   which            38036  2147557   0 /usr/bin/which ps\n7.883   sh               38037  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.884   ps               38037  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.917   sh               38038  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n7.918   cpuUsage.sh      38038  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n7.920   sed              38039  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.923   cat              38040  38038    0 /usr/bin/cat /proc/2240539/stat\n7.925   cat              38041  38038    0 /usr/bin/cat /proc/4193716/stat\n7.926   sleep            38042  38038    0 /usr/bin/sleep 1\n8.408   runc             38043  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process926607668 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.415   exe              38050  38043    0 /proc/self/exe init\n8.441   etcdctl          38053  38043    0 /usr/local/bin/etcdctl endpoint health\n8.464   16               38070  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n8.467   16               38071  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n8.625   drkonqi-coredum  38071  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 887-38069-0\n8.627   systemd-coredum  38070  1        0 /usr/lib/systemd/systemd-coredump\n8.929   sed              38082  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.932   cat              38083  38038    0 /usr/bin/cat /proc/2240539/stat\n8.934   cat              38085  38038    0 /usr/bin/cat /proc/4193716/stat\n9.131   9                38087  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n9.137   abrt-server      38088  1118     0 /usr/bin/abrt-server -s\n9.150   drkonqi-coredum  38087  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n9.166   abrt-handle-eve  38089  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312\n9.183   sh               38092  38089    0 /bin/sh -c abrt-action-save-package-data\\n\n9.184   abrt-action-sav  38092  38089    0 /usr/bin/abrt-action-save-package-data\n9.200   9                38095  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n9.205   plasma_waitforn  38095  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n9.249   sh               38097  38089    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n9.251   cat              38100  38098    0 /usr/bin/cat uid\n9.251   cut              38099  38097    0 /usr/bin/cut -d: -f1\n9.252   getent           38098  38097    0 /usr/bin/getent passwd 1000\n9.254   lscpu            38101  38097    0 /usr/bin/lscpu\n9.271   sh               38102  38089    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n9.273   runlevel         38103  38102    0 /usr/bin/runlevel\n9.285   sh               38104  38089    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n9.287   grep             38105  38104    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n9.289   grep             38106  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n9.291   grep             38107  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n9.292   abrt-action-cor  38108  38104    0 /usr/libexec/abrt-action-coredump -x\n9.360   abrt-action-gen  38109  38104    0 /usr/bin/abrt-action-generate-core-backtrace\n9.418   abrt-action-ana  38110  38104    0 /usr/bin/abrt-action-analyze-vulnerability\n9.421   eu-readelf       38112  38111    0 /usr/bin/eu-readelf -n coredump\n9.421   grep             38113  38111    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n9.421   sed              38114  38111    0 /usr/bin/sed s/[^0-9]//g\n9.424   gdb              38116  38115    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n9.442   iconv            38117  38116    0 /usr/bin/iconv -l\n9.546   abrt-action-ana  38126  38104    0 /usr/bin/abrt-action-analyze-c\n9.560   eu-unstrip       38127  38126    0 /usr/bin/eu-unstrip --core=./coredump -n\n9.580   abrt-action-lis  38128  38104    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n9.645   cat              38130  38129    0 /usr/bin/cat executable\n9.646   cat              38131  38129    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312/uid\n9.647   journalctl       38132  38129    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n9.659   abrt-action-cor  38133  38104    0 /usr/libexec/abrt-action-coredump -r\n9.703   abrt-handle-eve  38134  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.716   sh               38135  38134    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n9.717   dbus-send        38135  38134    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.719   sh               38136  38134    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n9.721   abrt-action-not  38137  38136    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.769   sh               38138  38137    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n9.770   reporter-system  38138  38137    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n11.630  16               38141  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n11.647  frpc             38141  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.214  runc             38147  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup kill --all 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 9\n17.234  runc             38153  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup delete 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n17.434  containerd-shim  38159  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 delete\n17.437  runc             38166  38159    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d109 --log-format json delete --force 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n17.485  sh               38176  38172    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc807bb6\n17.487  ethtool          38177  38176    0 /usr/sbin/ethtool -i vethc807bb6\n17.487  sed              38178  38176    0 /usr/bin/sed -n s/^driver: //p\n17.495  systemd-sysctl   38181  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc807bb6 --prefix=/net/ipv4/neigh/vethc807bb6 --prefix=/net/ipv6/conf/vethc807bb6 --prefix=/net/ipv6/neigh/vethc807bb6\n17.694  runc             38183  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup kill --all 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 9\n17.714  runc             38189  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup delete 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n17.919  containerd-shim  38195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a delete\n17.922  runc             38202  38195    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f8 --log-format json delete --force 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n17.961  systemd-sysctl   38207  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth31a3e53 --prefix=/net/ipv4/neigh/veth31a3e53 --prefix=/net/ipv6/conf/veth31a3e53 --prefix=/net/ipv6/neigh/veth31a3e53\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 35690,
  "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build",
  "pid": 35690,
  "ppid": 35320,
  "root_cargo_pid": 35320,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_out_dir": "/target/debug/build/memoffset-e7952ae2e0ab5922/out"
}
```

#### Record 17

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version",
    "--verbose"
  ],
  "build_script_related": true,
  "build_script_root_pid": 35690,
  "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 35694,
  "ppid": 35690,
  "root_cargo_pid": 35320,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_out_dir": "/target/debug/build/memoffset-e7952ae2e0ab5922/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 18

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--crate-name",
    "autocfg_9b38a2648c745ae9_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/memoffset-ba514fae611c68fc/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 35690,
  "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 35712,
  "ppid": 35690,
  "root_cargo_pid": 35320,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_build_script_out_dir": "/target/debug/build/memoffset-e7952ae2e0ab5922/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 19

```json
{
  "crate": "memoffset",
  "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "event_id": "bsrun:52155de9067b2dfc:fa2ad95e2825f774:e82d92e00ca94914",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
  "out_dir": "/target/debug/build/memoffset-e7952ae2e0ab5922/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
  "success": true,
  "target": null,
  "version": "0.9.1",
  "_owner": {
    "crate": "memoffset",
    "version": "0.9.1",
    "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
    "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
  "build_script_root_pid": 35690,
  "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 35694,
  "ppid": 35690,
  "root_cargo_pid": 35320,
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
    "autocfg_9b38a2648c745ae9_0",
    "--crate-type=lib",
    "--out-dir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/memoffset-ba514fae611c68fc/out",
    "--emit=llvm-ir",
    "--target",
    "riscv64gc-unknown-linux-gnu",
    "-"
  ],
  "build_script_related": true,
  "build_script_root_pid": 35690,
  "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 35712,
  "ppid": 35690,
  "root_cargo_pid": 35320,
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
  "time": "2026-07-14T01:32:26.826444+00:00",
  "crate": "memoffset",
  "version": "0.9.1",
  "architecture": "riscv64",
  "duration_seconds": 23.171538005117327,
  "trace_record_count": 19,
  "trace_owner_summary": {
    "owner_package_count": 3,
    "owner_packages": [
      {
        "crate": "doc-comment",
        "version": "0.3.4",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.4",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4/Cargo.toml"
      },
      {
        "crate": "autocfg",
        "version": "1.5.1",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#autocfg@1.5.1",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/autocfg-1.5.1/Cargo.toml"
      },
      {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "manifest_path": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 5,
    "owners": [
      {
        "crate": "memoffset",
        "version": "0.9.1",
        "event_count": 14,
        "kind_counts": {
          "native_trace_root_context": 1,
          "exec": 1,
          "used_input": 8,
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
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "workspace_root": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1"
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
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#doc-comment@0.3.4",
          "name": "doc-comment",
          "version": "0.3.4",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/doc-comment-0.3.4"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
          "name": "memoffset",
          "version": "0.9.1",
          "manifest_path": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1"
        }
      ],
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "exit_code": 0,
      "kind": "exec",
      "pid": 35587,
      "ppid": 35446,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:88c3273c7fed5c05:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
      "pid": 35587,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:2393373accbce763:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "5d577609ab01f59f82fd740ce11751156fbc52d16ca32e42e43b19f7c714ca3b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:109f0d0e6671dc05:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "7e36a3b9e005c511258788aa39cda071ef2932fcc34cec821316994a7749ee71",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:3ef2518c9e2caf40:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "e4034be838191d0d1e908d05794d859ab4bf3f3dc9dc41d0f013d48a133fe9e5",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:183b5baf9f03489c:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "8a066690afeaf612b53a771ba567e08f512351055e0db29e459db4d4886b63e3",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:0d0631077d4b1c7d:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "feea08b5110ffdb06e842907cf6971021f88da145841dc062cf4494cfb751007",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:83664ffcf266a7e2:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "1f908486d5288d26a226bba02d00536ac3427ae636d02b4904955e5d39890bde",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "used:cc:be7be0f00f695509:5e4afd5e3326021c:bfdb02a4b52dd2ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
      "pid": 35587,
      "sha256": "4120d7db7a1883e24ca0b5e64ac37d1fc169bf9f861a115dd2e48b95d15ab0bf",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
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
      "output": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "cargo_pkg_name": "memoffset",
      "cargo_pkg_version": "0.9.1",
      "context_path": "/tmp/native-trace-34378-1783992725358/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-34378-1783992725358/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 35587,
      "ppid": 35446,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
        "/target/debug/build/memoffset-e7952ae2e0ab5922",
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
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/rustcZf1DwX/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.2vkbzgddjjdr3spdcbtm1mi24.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.3akcve1auhbqzc04cdmfp84jv.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.47zv8c0pzt2duh8h1z0igs7f6.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.8hr31wfr9cvk7g033pmcwnxmc.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d0b3tmeirxwaom2y2212p8cft.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.dt38p64fbysvj64hm2w0q1i9u.00eyy9s.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/memoffset-e7952ae2e0ab5922",
          "kind": "object",
          "path": "/target/debug/build/memoffset-e7952ae2e0ab5922/build_script_build-e7952ae2e0ab5922.d8t5j259acgrfnr74ito04uw8.00eyy9s.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-35587-1783992729178548797.map",
      "pid": 35587,
      "ppid": 35446,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-35587-1783992729178548797.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
      "parsed_event_count": 531,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 532,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "utable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.580   rustc            37327  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.608   cc               37351  37326    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.610   cc               37356  37351    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcxNMyYm/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1bdrie6.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1bdrie6.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.613   collect2         37357  37356    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.615   ld.lld           37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n4.617   rust-lld         37358  37357    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRgWDgT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.650   cc               37380  37325    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.651   cc               37381  37327    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.651   cc               37382  37380    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcsEIO9w/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.652   cc               37383  37381    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcl34Ik1/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.655   collect2         37385  37382    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.656   collect2         37386  37383    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.658   ld.lld           37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n4.658   ld.lld           37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n4.660   rust-lld         37387  37385    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc3vw7AS.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.661   rust-lld         37388  37386    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccNSvnKV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.673   build-script-bu  37393  37290    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n4.684   cc               37423  37321    0 /tmp/native-trace-36904-1783992730833/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.686   cc               37424  37423    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcMYH21C/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.690   collect2         37425  37424    0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.692   ld.lld           37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n4.695   rust-lld         37426  37425    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccyEEbY0.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.708   build-script-bu  37444  37290    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n4.711   build-script-bu  37446  37290    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n4.726   cargo            37447  36863    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n4.737   build-script-bu  37449  37290    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n4.741   rustc            37450  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n4.743   rustc            37452  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.769   rustc            37465  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.769   rustc            37464  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.771   rustc            37466  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.771   rustc            37467  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=cbc0344642a3fe61 ...\n4.801   cc               37488  37467    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.802   cc               37493  37488    0 /usr/bin/cc -m64 /target/debug/build/rayon-core-c9a8f8c1754f6993/rustcXONVOl/symbols.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.0b0bvrkn0e5o9h0o8lkid3ftc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.2dp5wwd4a9lnm4ppm97olvcj0.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.44jb0glrsocryzhatv0vsxyal.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.68m4d37tgyrevjzmj6i0zoh74.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.9mwvpomdvpm22mu4p8acpm06t.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.dqhpsft46bux9fb5p2no0j2bc.1n73x60.rcgu.o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993.90i8jjqvig170rqso8l7r3hp7.1n73x60.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n4.806   collect2         37494  37493    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.807   ld.lld           37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/rayon-core-c9a8f8c1754f6993/build_script_build-c9a8f8c1754f6993 ...\n4.809   rust-lld         37495  37494    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccabJs5Y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.843   cc               37518  37464    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.844   cc               37519  37466    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.847   cc               37521  37519    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-deque-936e573f06352a39/rustcWyOZO2/symbols.o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.build_script_build.125d8aaaaa3abbde-cgu /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39.2vbz55vvcr1pkfsulhrzgf6u9.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.847   cc               37520  37518    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/rustcw5be7Q/symbols.o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.build_script_build.2e01dedb9631007a-cgu /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766.5j162o12s80rg0o64680w18i1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n4.848   collect2         37525  37521    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.851   ld.lld           37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-deque-936e573f06352a39/build_script_build-936e573f06352a39 ...\n4.851   collect2         37527  37520    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.854   rustc            37526  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.854   ld.lld           37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build_script_build-3b0c553f6b6de766 ...\n4.856   rust-lld         37528  37525    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc9XtiXz.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.857   rust-lld         37529  37527    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc2W9MEC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.863   build-script-bu  37531  37447    0 /target/debug/build/rayon-core-c9a8f8c1754f6993/build-script-build\n4.876   cc               37568  37465    0 /tmp/native-trace-36863-1783992730771/shims/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.877   cc               37570  37568    0 /usr/bin/cc -m64 /target/debug/build/crossbeam-utils-324949323a080052/rustcW31YEC/symbols.o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.build_script_build.2500fb02580134a6-cgu /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052.5iawe58mm3r33zqozumsjcycx.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n4.881   collect2         37571  37570    0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n4.884   ld.lld           37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/crossbeam-utils-324949323a080052/build_script_build-324949323a080052 ...\n4.886   rust-lld         37572  37571    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cccnztKg.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n4.911   build-script-bu  37590  37447    0 /target/debug/build/crossbeam-epoch-3b0c553f6b6de766/build-script-build\n4.915   build-script-bu  37592  37447    0 /target/debug/build/crossbeam-deque-936e573f06352a39/build-script-build\n4.927   build-script-bu  37594  37447    0 /target/debug/build/crossbeam-utils-324949323a080052/build-script-build\n4.933   rustc            37596  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_utils --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-utils-0.8.22/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.995   rustc            37606  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n4.997   rustc            37607  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.081   rustc            37621  37180    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=2bb0f49e2ccb2b73 ...\n5.117   rustc            37628  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.141   rustc            37636  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_epoch --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-epoch-0.9.20/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.202   rustc            37646  37290    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c73793a7c0eb3dd6 ...\n5.266   rustc            37653  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name crossbeam_deque --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/crossbeam-deque-0.8.7/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --allow=clippy::lint_groups_priority --allow=clippy::declare_interior_mutable_const --check-cfg cfg(crossbeam_loom) --check-cfg ...\n5.344   rustc            37661  37447    0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name rayon_core --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"web_spin_lock\")) -C metadata=c16cb3cec9db833d ...\n7.879   sh               38036  2147557   0 /bin/sh -c which ps\n7.880   which            38036  2147557   0 /usr/bin/which ps\n7.883   sh               38037  2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.884   ps               38037  2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n7.917   sh               38038  2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n7.918   cpuUsage.sh      38038  2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n7.920   sed              38039  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n7.923   cat              38040  38038    0 /usr/bin/cat /proc/2240539/stat\n7.925   cat              38041  38038    0 /usr/bin/cat /proc/4193716/stat\n7.926   sleep            38042  38038    0 /usr/bin/sleep 1\n8.408   runc             38043  3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process926607668 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n8.415   exe              38050  38043    0 /proc/self/exe init\n8.441   etcdctl          38053  38043    0 /usr/local/bin/etcdctl endpoint health\n8.464   16               38070  1        0 /proc/self/fd/16 --deserialize 145 --log-level info --log-target journal-or-kmsg\n8.467   16               38071  1        0 /proc/self/fd/16 --deserialize 157 --log-level info --log-target journal-or-kmsg\n8.625   drkonqi-coredum  38071  1        0 /usr/libexec/drkonqi-coredump-processor --boot-id c4b3b46df1b843dca22eb5d84b2a958a --instance 887-38069-0\n8.627   systemd-coredum  38070  1        0 /usr/lib/systemd/systemd-coredump\n8.929   sed              38082  38038    0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n8.932   cat              38083  38038    0 /usr/bin/cat /proc/2240539/stat\n8.934   cat              38085  38038    0 /usr/bin/cat /proc/4193716/stat\n9.131   9                38087  4003047   0 /proc/self/fd/9 --deserialize 41 --log-level info --log-target auto\n9.137   abrt-server      38088  1118     0 /usr/bin/abrt-server -s\n9.150   drkonqi-coredum  38087  4003047   0 /usr/libexec/drkonqi-coredump-launcher\n9.166   abrt-handle-eve  38089  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e post-create -- /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312\n9.183   sh               38092  38089    0 /bin/sh -c abrt-action-save-package-data\\n\n9.184   abrt-action-sav  38092  38089    0 /usr/bin/abrt-action-save-package-data\n9.200   9                38095  4003047   0 /proc/self/fd/9 --deserialize 44 --log-level info --log-target auto\n9.205   plasma_waitforn  38095  4003047   0 /usr/bin/plasma_waitforname org.freedesktop.Notifications\n9.249   sh               38097  38089    0 /bin/sh -c # uid file is missing for problems visible to all users\\n        # (oops scanner is often set up to not create it).\\n        # Rec\n9.251   cat              38100  38098    0 /usr/bin/cat uid\n9.251   cut              38099  38097    0 /usr/bin/cut -d: -f1\n9.252   getent           38098  38097    0 /usr/bin/getent passwd 1000\n9.254   lscpu            38101  38097    0 /usr/bin/lscpu\n9.271   sh               38102  38089    0 /bin/sh -c runlevel >runlevel 2>&1\\n        exit 0\\n\n9.273   runlevel         38103  38102    0 /usr/bin/runlevel\n9.285   sh               38104  38089    0 /bin/sh -c if grep '^TracerPid:[[:space:]]*[123456789]' proc_pid_status >/dev/null 2>&1; then\\n            # We see 'TracerPid: <nonzero>\" i\n9.287   grep             38105  38104    0 /usr/bin/grep ^TracerPid:[[:space:]]*[123456789] proc_pid_status\n9.289   grep             38106  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_ALL=1 environ\n9.291   grep             38107  38104    0 /usr/bin/grep -q ^ABRT_IGNORE_CCPP=1 environ\n9.292   abrt-action-cor  38108  38104    0 /usr/libexec/abrt-action-coredump -x\n9.360   abrt-action-gen  38109  38104    0 /usr/bin/abrt-action-generate-core-backtrace\n9.418   abrt-action-ana  38110  38104    0 /usr/bin/abrt-action-analyze-vulnerability\n9.421   eu-readelf       38112  38111    0 /usr/bin/eu-readelf -n coredump\n9.421   grep             38113  38111    0 /usr/bin/grep -m1 -o cursig: *[0-9]*\n9.421   sed              38114  38111    0 /usr/bin/sed s/[^0-9]//g\n9.424   gdb              38116  38115    0 /usr/libexec/gdb --batch -ex python exec(open(\"/usr/libexec/abrt-gdb-exploitable\").read()) -ex core-file ./coredump -ex abrt-exploitable 4 ./exploitable\n9.442   iconv            38117  38116    0 /usr/bin/iconv -l\n9.546   abrt-action-ana  38126  38104    0 /usr/bin/abrt-action-analyze-c\n9.560   eu-unstrip       38127  38126    0 /usr/bin/eu-unstrip --core=./coredump -n\n9.580   abrt-action-lis  38128  38104    0 /usr/bin/abrt-action-list-dsos -m maps -o dso_list\n9.645   cat              38130  38129    0 /usr/bin/cat executable\n9.646   cat              38131  38129    0 /usr/bin/cat /var/spool/abrt/ccpp-2026-07-14-10:32:17.647031-35312/uid\n9.647   journalctl       38132  38129    0 /usr/bin/journalctl -q -b --since=-3m -n 99 _COMM=drkonqi-coredump-launcher _UID=1000\n9.659   abrt-action-cor  38133  38104    0 /usr/libexec/abrt-action-coredump -r\n9.703   abrt-handle-eve  38134  38088    0 /usr/libexec/abrt-handle-event -i --nice 10 -e notify-dup -- /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.716   sh               38135  38134    0 /bin/sh -c dbus-send --system --type=signal \\\\n           /org/freedesktop/Problems2 \\\\n           org.freedesktop.Problems2.ReloadProblem \\\\n\n9.717   dbus-send        38135  38134    0 /usr/bin/dbus-send --system --type=signal /org/freedesktop/Problems2 org.freedesktop.Problems2.ReloadProblem string:/var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.719   sh               38136  38134    0 /bin/sh -c abrt-action-notify -d $DUMP_DIR\\n        true # ignore failures because we want to run all 'notify' events\n9.721   abrt-action-not  38137  38136    0 /usr/bin/abrt-action-notify -d /var/spool/abrt/ccpp-2026-07-14-05:39:31.181847-4010626\n9.769   sh               38138  38137    0 /bin/sh -c reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 \\\\n                                 -F /etc/libreport/plug\n9.770   reporter-system  38138  38137    0 /usr/bin/reporter-systemd-journal --message-id 5ab0271ecf1941a2b89299716e880661 -F /etc/libreport/plugins/catalog_journal_ccpp_format.conf\n11.630  16               38141  1        0 /proc/self/fd/16 --deserialize 136 --log-level info --log-target journal-or-kmsg\n11.647  frpc             38141  1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n17.214  runc             38147  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup kill --all 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 9\n17.234  runc             38153  32797    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 --log-format json --systemd-cgroup delete 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n17.434  containerd-shim  38159  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904 delete\n17.437  runc             38166  38159    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d109 --log-format json delete --force 9799147a26031b3c38ec0fc17ab41fc490f92531d3088d40ae6fd387904d1091\n17.485  sh               38176  38172    0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethc807bb6\n17.487  ethtool          38177  38176    0 /usr/sbin/ethtool -i vethc807bb6\n17.487  sed              38178  38176    0 /usr/bin/sed -n s/^driver: //p\n17.495  systemd-sysctl   38181  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc807bb6 --prefix=/net/ipv4/neigh/vethc807bb6 --prefix=/net/ipv6/conf/vethc807bb6 --prefix=/net/ipv6/neigh/vethc807bb6\n17.694  runc             38183  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup kill --all 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 9\n17.714  runc             38189  33908    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a --log-format json --systemd-cgroup delete 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n17.919  containerd-shim  38195  1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a delete\n17.922  runc             38202  38195    0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f8 --log-format json delete --force 1dfa759d5a2317fd653eeeba570b29c83d9e106237a17d4d1232fa4bd8a13f82\n17.961  systemd-sysctl   38207  38172    0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth31a3e53 --prefix=/net/ipv4/neigh/veth31a3e53 --prefix=/net/ipv6/conf/veth31a3e53 --prefix=/net/ipv6/neigh/veth31a3e53\n"
    },
    {
      "argv": [
        "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 35690,
      "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build",
      "pid": 35690,
      "ppid": 35320,
      "root_cargo_pid": 35320,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version",
        "--verbose"
      ],
      "build_script_related": true,
      "build_script_root_pid": 35690,
      "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 35694,
      "ppid": 35690,
      "root_cargo_pid": 35320,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--crate-name",
        "autocfg_9b38a2648c745ae9_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/memoffset-ba514fae611c68fc/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 35690,
      "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 35712,
      "ppid": 35690,
      "root_cargo_pid": 35320,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "memoffset",
      "cwd": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "event_id": "bsrun:52155de9067b2dfc:fa2ad95e2825f774:e82d92e00ca94914",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/memoffset-e7952ae2e0ab5922/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
      "out_dir": "/target/debug/build/memoffset-e7952ae2e0ab5922/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
      "success": true,
      "target": null,
      "version": "0.9.1",
      "_owner": {
        "crate": "memoffset",
        "version": "0.9.1",
        "package_id": "path+file:///tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1#memoffset@0.9.1",
        "manifest_dir": "/tmp/crate-build-riscv64-yynbm5y4/src/memoffset-0.9.1",
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
      "build_script_root_pid": 35690,
      "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 35694,
      "ppid": 35690,
      "root_cargo_pid": 35320,
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
        "autocfg_9b38a2648c745ae9_0",
        "--crate-type=lib",
        "--out-dir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/memoffset-ba514fae611c68fc/out",
        "--emit=llvm-ir",
        "--target",
        "riscv64gc-unknown-linux-gnu",
        "-"
      ],
      "build_script_related": true,
      "build_script_root_pid": 35690,
      "build_script_target_dir": "memoffset-e7952ae2e0ab5922",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 35712,
      "ppid": 35690,
      "root_cargo_pid": 35320,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 170,
    "crate": "memoffset",
    "version": "0.9.1",
    "crate_id": "35941",
    "version_id": "1094992",
    "downloads": 146074431,
    "cumulative_downloads": 39350835810,
    "cumulative_share_of_global": 0.14712369072431145,
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
