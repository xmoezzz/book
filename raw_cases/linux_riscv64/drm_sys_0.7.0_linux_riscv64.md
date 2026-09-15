# `drm-sys` `0.7.0`

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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
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
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
    "/target/debug/build/drm-sys-1e3689cce830f247",
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
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1060028-1783999231948751731.map",
  "pid": 1060028,
  "ppid": 1059989,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1060028-1783999231948751731.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "workspace_root": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
      "name": "drm-sys",
      "version": "0.7.0",
      "manifest_path": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.5",
      "name": "linux-raw-sys",
      "version": "0.6.5",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5"
    }
  ],
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1060028,
  "ppid": 1059989,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:e33b29020768c97e:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
  "pid": 1060028,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:5fbe343ab9047dae:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "aa5539d5982eda413ccf9611c2ca4b39938f46d1093f721a065c152573a8a382",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:171f8e5f2516cc1c:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "78b93e2551c7515d05917062d84d42be2eb5348a2c043da54e5ffa23dfd0cce6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:74fcf1b2926c8fa3:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "64ea9329a1b8eb767e40c95ab1a2b1a2115e88967eb9fe3a759933a91343982d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:28287779ee663a15:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "92c7c12d452d2294c265bd36cee2a444f2804faf9248601cda6c05bf2d8c1bd0",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:048abc7737450e09:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "ce51f2ebe788268b63ae43d7050e0f8b14220d41ef6f640a76503df4d1fc0c30",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "used:cc:ba39c64aa35b1f85:cec345d05d8498cc:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
  "pid": 1060028,
  "sha256": "da6811dae70cb6083d2767cac1d18d10434f5e6665ae78c6c23e6f8961e7e65d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
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
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "/tmp/native-trace-1058298-1783999227502/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1058298-1783999227502/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1060028,
  "ppid": 1059989,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
    "/target/debug/build/drm-sys-1e3689cce830f247",
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
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1060028-1783999231948751731.map",
  "pid": 1060028,
  "ppid": 1059989,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1060028-1783999231948751731.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
  "parsed_event_count": 676,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 678,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n10.771  rustc            1063045 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n11.114  rustc            1063093 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n11.199  cc               1063112 1062799   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.200  cc               1063113 1063112   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.204  collect2         1063115 1063113   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs ...\n11.207  ld.lld           1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.211  rust-lld         1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n11.255  rustc            1063136 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n11.327  cc               1063159 1063136   0 /tmp/native-trace-1061857-1783999237062/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.330  cc               1063161 1063159   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.335  collect2         1063162 1063161   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.338  ld.lld           1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n11.343  rust-lld         1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.454  rustc            1063190 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=480ed063e9b929e7 ...\n11.475  build-script-bu  1063196 1062716   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n11.478  aarch64-linux-g  1063197 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family\n11.478  cc1              1063198 1063197   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.484  aarch64-linux-g  1063203 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n11.486  aarch64-linux-g  1063204 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil\n11.487  cc1              1063205 1063204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.492  aarch64-linux-g  1063206 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n11.495  aarch64-linux-g  1063207 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -c /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c\n11.497  cc1              1063209 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c -quiet -dumpbase flag_check.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -O0 -Wall -Wextra -Wno-unused-value -ffunction-sections -fdata-sections -fPIC -fasynchronous-unwind-tables ...\n11.508  as               1063211 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check /tmp/ccshdZxV.s\n11.518  aarch64-linux-g  1063212 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -c src/parser.c\n11.520  cc1              1063213 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/parser.c -quiet -dumpbase parser.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n11.606  cc               1063218 1062936   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.607  cc               1063219 1063218   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.609  collect2         1063220 1063219   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs ...\n11.611  ld.lld           1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.612  rust-lld         1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n11.742  rustc            1063239 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0fb8ee0bf7492b0e ...\n12.687  rustc            1063282 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.769  cc               1063294 1063282   0 /tmp/native-trace-1057733-1783999224707/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.770  cc               1063295 1063294   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.772  collect2         1063296 1063295   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.774  ld.lld           1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n12.775  rust-lld         1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.824  build-script-bu  1063315 1058460   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n12.829  rustc            1063317 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.875  rustc            1063322 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.958  cc               1063333 1063322   0 /tmp/native-trace-1057721-1783999224654/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.959  cc               1063334 1063333   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.962  collect2         1063335 1063334   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.964  ld.lld           1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n12.966  rust-lld         1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.020  build-script-bu  1063354 1058268   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n13.027  rustc            1063356 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n13.032  cargo            1063357 1062789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n13.044  rustc            1063361 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.064  rustc            1063371 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n13.064  rustc            1063369 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n13.064  rustc            1063370 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n13.107  cc               1063384 1063370   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n13.108  cc               1063385 1063384   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n13.110  collect2         1063386 1063385   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.111  ld.lld           1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n13.113  rust-lld         1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.139  rustc            1063410 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n13.150  build-script-bu  1063415 1063357   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n13.154  rustc            1063417 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n13.366  runc             1063426 1057301   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 --log-format json --systemd-cgroup kill --all bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8 9\n13.384  runc             1063432 1057301   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 --log-format json --systemd-cgroup delete bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8\n13.564  containerd-shim  1063438 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 delete\n13.567  runc             1063444 1063438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce --log-format json delete --force bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8\n13.599  sh               1063455 1063452   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth5180d16\n13.600  ethtool          1063456 1063455   0 /usr/sbin/ethtool -i veth5180d16\n13.600  sed              1063457 1063455   0 /usr/bin/sed -n s/^driver: //p\n13.606  systemd-sysctl   1063460 1063452   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5180d16 --prefix=/net/ipv4/neigh/veth5180d16 --prefix=/net/ipv6/conf/veth5180d16 --prefix=/net/ipv6/neigh/veth5180d16\n13.817  rustc            1063480 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n13.861  cc               1063497 1063480   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n13.861  cc               1063498 1063497   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n13.864  collect2         1063499 1063498   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.865  ld.lld           1063500 1063499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n13.866  rust-lld         1063500 1063499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.929  build-script-bu  1063518 1063357   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n13.931  riscv64-linux-g  1063519 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami\n13.932  cc1              1063520 1063519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 8236753969842890862detect_compiler_family.c -dumpbase-ext .c\n13.939  riscv64-linux-g  1063521 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -?\n13.941  riscv64-linux-g  1063522 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami\n13.943  cc1              1063523 1063522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 5787956455649300018detect_compiler_family.c -dumpbase-ext .c\n13.949  riscv64-linux-g  1063524 1063518   0 /usr/bin/riscv64-linux-gnu-gcc \n13.952  riscv64-linux-g  1063525 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check -c /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c\n13.953  cc1              1063526 1063525   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase flag_check.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -O0 -Wall ...\n13.960  as               1063527 1063525   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check /tmp/cc2YtBBh.s\n13.964  riscv64-linux-g  1063528 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o -c src/parser.c ...\n13.965  cc1              1063529 1063528   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.272  as               1063530 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I src -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o /tmp/ccrLIV4k.s\n14.571  aarch64-linux-g  1063531 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o -c src/scanner.c\n14.572  cc1              1063532 1063531   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/scanner.c -quiet -dumpbase scanner.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n14.602  as               1063533 1063531   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I src -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o /tmp/ccBnpmKp.s\n14.614  aarch64-linux-g  1063534 1063196   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/libtree-sitter-c-sharp.a /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o\n14.621  aarch64-linux-g  1063535 1063196   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/libtree-sitter-c-sharp.a\n14.632  rustc            1063537 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c_sharp --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0940ba3f25045552 ...\n16.280  16               1063995 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n16.291  frpc             1063995 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.722  as               1064067 1063528   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o /tmp/cc2DdQzG.s\n16.978  riscv64-linux-g  1064068 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o -c src/scanner.c ...\n16.979  cc1              1064069 1064068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/scanner.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase ea708c7824d36062-scanner.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n17.003  as               1064070 1064068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o /tmp/cctYRJTb.s\n17.009  riscv64-linux-g  1064071 1063518   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o\n17.036  riscv64-linux-g  1064072 1063518   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a\n17.066  rustc            1064074 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c_sharp --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1087bf4968f071f2 ...\n17.818  cross            1064081 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.819  rustc            1064084 1064081   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.823  rustc            1064084 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.835  rustc            1064096 1064081   0 /home/xmoe/.cargo/bin/rustc -vV\n17.840  rustc            1064096 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.849  cargo            1064106 1064081   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.853  cargo            1064106 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.863  rustc            1064115 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.873  rustc            1064117 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.884  rustc            1064121 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.002  rustc            1064126 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.023  rustc            1064128 1064081   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.027  rustc            1064128 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.039  docker           1064140 1064081   0 /usr/bin/docker --help\n18.052  docker           1064152 1064081   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.062  runc             1064162 1599     0 /usr/bin/runc --version\n18.064  docker-init      1064168 1599     0 /usr/bin/docker-init --version\n18.066  docker           1064169 1064081   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.072  runc             1064175 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2627381297 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.077  exe              1064186 1064175   0 /proc/self/exe init\n18.077  runc             1064187 1599     0 /usr/bin/runc --version\n18.080  docker-init      1064201 1599     0 /usr/bin/docker-init --version\n18.093  etcdctl          1064190 1064175   0 /usr/local/bin/etcdctl endpoint health\n18.099  rustup           1064207 1064081   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.105  rustup           1064221 1064081   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.128  rustup           1064230 1064081   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.149  cross            1064239 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n18.150  uname            1064242 1064081   0 /usr/bin/uname -r\n18.150  rustc            1064243 1064239   0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.155  rustc            1064243 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.166  rustc            1064255 1064239   0 /home/xmoe/.cargo/bin/rustc -vV\n18.167  docker           1064256 1064081   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.172  rustc            1064255 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.181  cargo            1064278 1064239   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.187  cargo            1064278 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.198  rustc            1064287 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.208  rustc            1064291 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.208  systemd-sysctl   1064292 1064289   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth739a70e --prefix=/net/ipv4/neigh/veth739a70e --prefix=/net/ipv6/conf/veth739a70e --prefix=/net/ipv6/neigh/veth739a70e\n18.209  systemd-sysctl   1064293 1064290   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2e00b52 --prefix=/net/ipv4/neigh/veth2e00b52 --prefix=/net/ipv6/conf/veth2e00b52 --prefix=/net/ipv6/neigh/veth2e00b52\n18.219  containerd-shim  1064318 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 start\n18.220  rustc            1064325 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.222  containerd-shim  1064335 1064318   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 -address /var/run/docker/containerd/containerd.sock\n18.226  runc             1064344 1064335   0 \n18.232  exe              1064356 1064344   0 /proc/self/exe init\n18.265  exe              1064365 1064344   0 /proc/1599/exe -exec-root=/var/run/docker 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 d7da31e8f8e1\n18.284  exe              1064373 1599     0 /proc/self/exe /var/run/docker/netns/994a49d4080b all false\n18.331  runc             1064395 1064335   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd43 --log-format json --systemd-cgroup start 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0\n18.336  sh               1064358 1064335   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.337  cargo            1064402 1064358   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.347  cargo-native-tr  1064402 1064358   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.350  cargo            1064403 1064402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.360  rustc            1064404 1064403   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.371  rustc            1064406 1064403   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1060237,
  "build_script_target_dir": "drm-sys-1e3689cce830f247",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
  "pid": 1060237,
  "ppid": 1059953,
  "root_cargo_pid": 1059953,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "_build_script_out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out"
}
```

#### Record 16

```json
{
  "crate": "drm-sys",
  "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "event_id": "bsrun:56a6630f5eb0ce95:fc545b1ff076f511:750ef5a1d5bc27c7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
  "out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
  "success": true,
  "target": null,
  "version": "0.7.0",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:20:55.599307+00:00",
  "crate": "drm-sys",
  "version": "0.7.0",
  "architecture": "riscv64",
  "duration_seconds": 32.680139891803265,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 3,
    "owner_packages": [
      {
        "crate": "linux-raw-sys",
        "version": "0.6.5",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.5",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
      },
      {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "manifest_path": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "drm-sys",
        "version": "0.7.0",
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
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "workspace_root": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
          "name": "drm-sys",
          "version": "0.7.0",
          "manifest_path": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#linux-raw-sys@0.6.5",
          "name": "linux-raw-sys",
          "version": "0.6.5",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/linux-raw-sys-0.6.5"
        }
      ],
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1060028,
      "ppid": 1059989,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:e33b29020768c97e:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
      "pid": 1060028,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:5fbe343ab9047dae:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "aa5539d5982eda413ccf9611c2ca4b39938f46d1093f721a065c152573a8a382",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:171f8e5f2516cc1c:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "78b93e2551c7515d05917062d84d42be2eb5348a2c043da54e5ffa23dfd0cce6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:74fcf1b2926c8fa3:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "64ea9329a1b8eb767e40c95ab1a2b1a2115e88967eb9fe3a759933a91343982d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:28287779ee663a15:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "92c7c12d452d2294c265bd36cee2a444f2804faf9248601cda6c05bf2d8c1bd0",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:048abc7737450e09:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "ce51f2ebe788268b63ae43d7050e0f8b14220d41ef6f640a76503df4d1fc0c30",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "used:cc:ba39c64aa35b1f85:cec345d05d8498cc:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
      "pid": 1060028,
      "sha256": "da6811dae70cb6083d2767cac1d18d10434f5e6665ae78c6c23e6f8961e7e65d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
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
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "/tmp/native-trace-1058298-1783999227502/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1058298-1783999227502/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1060028,
      "ppid": 1059989,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
        "/target/debug/build/drm-sys-1e3689cce830f247",
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
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcRlO5km/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.1xtas5e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.1xtas5e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.1xtas5e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.1xtas5e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.1xtas5e.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.1xtas5e.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1060028-1783999231948751731.map",
      "pid": 1060028,
      "ppid": 1059989,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1060028-1783999231948751731.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
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
      "parsed_event_count": 676,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 678,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n10.771  rustc            1063045 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n11.114  rustc            1063093 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n11.199  cc               1063112 1062799   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.200  cc               1063113 1063112   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.204  collect2         1063115 1063113   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs ...\n11.207  ld.lld           1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.211  rust-lld         1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n11.255  rustc            1063136 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n11.327  cc               1063159 1063136   0 /tmp/native-trace-1061857-1783999237062/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.330  cc               1063161 1063159   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n11.335  collect2         1063162 1063161   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.338  ld.lld           1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n11.343  rust-lld         1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.454  rustc            1063190 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=480ed063e9b929e7 ...\n11.475  build-script-bu  1063196 1062716   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n11.478  aarch64-linux-g  1063197 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family\n11.478  cc1              1063198 1063197   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.484  aarch64-linux-g  1063203 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n11.486  aarch64-linux-g  1063204 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil\n11.487  cc1              1063205 1063204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n11.492  aarch64-linux-g  1063206 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n11.495  aarch64-linux-g  1063207 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -c /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c\n11.497  cc1              1063209 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c -quiet -dumpbase flag_check.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -O0 -Wall -Wextra -Wno-unused-value -ffunction-sections -fdata-sections -fPIC -fasynchronous-unwind-tables ...\n11.508  as               1063211 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check /tmp/ccshdZxV.s\n11.518  aarch64-linux-g  1063212 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -c src/parser.c\n11.520  cc1              1063213 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/parser.c -quiet -dumpbase parser.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n11.606  cc               1063218 1062936   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.607  cc               1063219 1063218   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n11.609  collect2         1063220 1063219   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs ...\n11.611  ld.lld           1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n11.612  rust-lld         1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n11.742  rustc            1063239 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0fb8ee0bf7492b0e ...\n12.687  rustc            1063282 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.769  cc               1063294 1063282   0 /tmp/native-trace-1057733-1783999224707/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.770  cc               1063295 1063294   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.772  collect2         1063296 1063295   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.774  ld.lld           1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n12.775  rust-lld         1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n12.824  build-script-bu  1063315 1058460   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n12.829  rustc            1063317 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.875  rustc            1063322 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n12.958  cc               1063333 1063322   0 /tmp/native-trace-1057721-1783999224654/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.959  cc               1063334 1063333   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n12.962  collect2         1063335 1063334   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n12.964  ld.lld           1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n12.966  rust-lld         1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.020  build-script-bu  1063354 1058268   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n13.027  rustc            1063356 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n13.032  cargo            1063357 1062789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n13.044  rustc            1063361 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n13.064  rustc            1063371 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n13.064  rustc            1063369 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n13.064  rustc            1063370 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n13.107  cc               1063384 1063370   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n13.108  cc               1063385 1063384   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n13.110  collect2         1063386 1063385   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.111  ld.lld           1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n13.113  rust-lld         1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.139  rustc            1063410 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n13.150  build-script-bu  1063415 1063357   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n13.154  rustc            1063417 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n13.366  runc             1063426 1057301   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 --log-format json --systemd-cgroup kill --all bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8 9\n13.384  runc             1063432 1057301   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 --log-format json --systemd-cgroup delete bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8\n13.564  containerd-shim  1063438 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f3 delete\n13.567  runc             1063444 1063438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce --log-format json delete --force bd357c13b8897ef35ecc5e77c0992485eb81215fc727823f6e8bc2799f354ce8\n13.599  sh               1063455 1063452   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth5180d16\n13.600  ethtool          1063456 1063455   0 /usr/sbin/ethtool -i veth5180d16\n13.600  sed              1063457 1063455   0 /usr/bin/sed -n s/^driver: //p\n13.606  systemd-sysctl   1063460 1063452   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5180d16 --prefix=/net/ipv4/neigh/veth5180d16 --prefix=/net/ipv6/conf/veth5180d16 --prefix=/net/ipv6/neigh/veth5180d16\n13.817  rustc            1063480 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n13.861  cc               1063497 1063480   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n13.861  cc               1063498 1063497   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustcWDcGDn/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0ss7sm9.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0ss7sm9.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n13.864  collect2         1063499 1063498   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n13.865  ld.lld           1063500 1063499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n13.866  rust-lld         1063500 1063499   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccX0TuZJ.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n13.929  build-script-bu  1063518 1063357   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n13.931  riscv64-linux-g  1063519 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami\n13.932  cc1              1063520 1063519   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/8236753969842890862detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 8236753969842890862detect_compiler_family.c -dumpbase-ext .c\n13.939  riscv64-linux-g  1063521 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -?\n13.941  riscv64-linux-g  1063522 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -E /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami\n13.943  cc1              1063523 1063522   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -E -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/5787956455649300018detect_compiler_fami -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -fstack-protector-strong -Wformat -Wformat-security -dumpbase 5787956455649300018detect_compiler_family.c -dumpbase-ext .c\n13.949  riscv64-linux-g  1063524 1063518   0 /usr/bin/riscv64-linux-gnu-gcc \n13.952  riscv64-linux-g  1063525 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -march=rv64gc -mabi=lp64d -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check -c /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c\n13.953  cc1              1063526 1063525   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -imultilib . -imultiarch riscv64-linux-gnu /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase flag_check.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc -O0 -Wall ...\n13.960  as               1063527 1063525   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/flag_check /tmp/cc2YtBBh.s\n13.964  riscv64-linux-g  1063528 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o -c src/parser.c ...\n13.965  cc1              1063529 1063528   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/parser.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase ea708c7824d36062-parser.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n14.272  as               1063530 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I src -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o /tmp/ccrLIV4k.s\n14.571  aarch64-linux-g  1063531 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o -c src/scanner.c\n14.572  cc1              1063532 1063531   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/scanner.c -quiet -dumpbase scanner.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n14.602  as               1063533 1063531   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I src -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o /tmp/ccBnpmKp.s\n14.614  aarch64-linux-g  1063534 1063196   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/libtree-sitter-c-sharp.a /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-scanner.o\n14.621  aarch64-linux-g  1063535 1063196   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/libtree-sitter-c-sharp.a\n14.632  rustc            1063537 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c_sharp --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0940ba3f25045552 ...\n16.280  16               1063995 1        0 /proc/self/fd/16 --deserialize 126 --log-level info --log-target journal-or-kmsg\n16.291  frpc             1063995 1        0 /usr/local/bin/frpc -c /etc/frp/frpc.toml\n16.722  as               1064067 1063528   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o /tmp/cc2DdQzG.s\n16.978  riscv64-linux-g  1064068 1063518   0 /usr/bin/riscv64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -march=rv64gc -mabi=lp64d -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o -c src/scanner.c ...\n16.979  cc1              1064069 1064068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1 -quiet -I src -imultilib . -imultiarch riscv64-linux-gnu src/scanner.c -quiet -dumpdir /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ -dumpbase ea708c7824d36062-scanner.c -dumpbase-ext .c -march=rv64gc -mabi=lp64d -misa-spec=2.2 -march=rv64imafdc ...\n17.003  as               1064070 1064068   0 /usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as -I src --gdwarf-4 --traditional-format -fpic -march=rv64gc -march=rv64imafdc -mabi=lp64d -misa-spec=2.2 -o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o /tmp/cctYRJTb.s\n17.009  riscv64-linux-g  1064071 1063518   0 /usr/bin/riscv64-linux-gnu-ar cqD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-parser.o /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/ea708c7824d36062-scanner.o\n17.036  riscv64-linux-g  1064072 1063518   0 /usr/bin/riscv64-linux-gnu-ar sD /target/riscv64gc-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-c7ad32e373eacf33/out/libtree-sitter-c-sharp.a\n17.066  rustc            1064074 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_c_sharp --edition=2021 bindings/rust/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=1087bf4968f071f2 ...\n17.818  cross            1064081 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n17.819  rustc            1064084 1064081   0 /home/xmoe/.cargo/bin/rustc --print target-list\n17.823  rustc            1064084 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n17.835  rustc            1064096 1064081   0 /home/xmoe/.cargo/bin/rustc -vV\n17.840  rustc            1064096 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.849  cargo            1064106 1064081   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.853  cargo            1064106 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n17.863  rustc            1064115 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.873  rustc            1064117 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.884  rustc            1064121 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.002  rustc            1064126 1064106   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.023  rustc            1064128 1064081   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n18.027  rustc            1064128 1064081   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n18.039  docker           1064140 1064081   0 /usr/bin/docker --help\n18.052  docker           1064152 1064081   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n18.062  runc             1064162 1599     0 /usr/bin/runc --version\n18.064  docker-init      1064168 1599     0 /usr/bin/docker-init --version\n18.066  docker           1064169 1064081   0 /usr/bin/docker info -f {{.SecurityOptions}}\n18.072  runc             1064175 3660     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 --log-format json --systemd-cgroup exec --process /tmp/runc-process2627381297 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469 6d7e9c16e34641852cad1d2b5725a3e3646c3212da594ab43be6788c469ab26a\n18.077  exe              1064186 1064175   0 /proc/self/exe init\n18.077  runc             1064187 1599     0 /usr/bin/runc --version\n18.080  docker-init      1064201 1599     0 /usr/bin/docker-init --version\n18.093  etcdctl          1064190 1064175   0 /usr/local/bin/etcdctl endpoint health\n18.099  rustup           1064207 1064081   0 /home/xmoe/.cargo/bin/rustup toolchain list\n18.105  rustup           1064221 1064081   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n18.128  rustup           1064230 1064081   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n18.149  cross            1064239 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n18.150  uname            1064242 1064081   0 /usr/bin/uname -r\n18.150  rustc            1064243 1064239   0 /home/xmoe/.cargo/bin/rustc --print target-list\n18.155  rustc            1064243 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n18.166  rustc            1064255 1064239   0 /home/xmoe/.cargo/bin/rustc -vV\n18.167  docker           1064256 1064081   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n18.172  rustc            1064255 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.181  cargo            1064278 1064239   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.187  cargo            1064278 1064239   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n18.198  rustc            1064287 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.208  rustc            1064291 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n18.208  systemd-sysctl   1064292 1064289   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth739a70e --prefix=/net/ipv4/neigh/veth739a70e --prefix=/net/ipv6/conf/veth739a70e --prefix=/net/ipv6/neigh/veth739a70e\n18.209  systemd-sysctl   1064293 1064290   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth2e00b52 --prefix=/net/ipv4/neigh/veth2e00b52 --prefix=/net/ipv6/conf/veth2e00b52 --prefix=/net/ipv6/neigh/veth2e00b52\n18.219  containerd-shim  1064318 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 start\n18.220  rustc            1064325 1064278   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n18.222  containerd-shim  1064335 1064318   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 -address /var/run/docker/containerd/containerd.sock\n18.226  runc             1064344 1064335   0 \n18.232  exe              1064356 1064344   0 /proc/self/exe init\n18.265  exe              1064365 1064344   0 /proc/1599/exe -exec-root=/var/run/docker 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0 d7da31e8f8e1\n18.284  exe              1064373 1599     0 /proc/self/exe /var/run/docker/netns/994a49d4080b all false\n18.331  runc             1064395 1064335   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd43 --log-format json --systemd-cgroup start 98b92d5b13930e5a35420068078562548c580fede8798713ea920f7cd435e7b0\n18.336  sh               1064358 1064335   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n18.337  cargo            1064402 1064358   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.347  cargo-native-tr  1064402 1064358   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n18.350  cargo            1064403 1064402   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n18.360  rustc            1064404 1064403   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n18.371  rustc            1064406 1064403   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n"
    },
    {
      "argv": [
        "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1060237,
      "build_script_target_dir": "drm-sys-1e3689cce830f247",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
      "pid": 1060237,
      "ppid": 1059953,
      "root_cargo_pid": 1059953,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "drm-sys",
      "cwd": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "event_id": "bsrun:56a6630f5eb0ce95:fc545b1ff076f511:750ef5a1d5bc27c7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
      "out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
      "success": true,
      "target": null,
      "version": "0.7.0",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-riscv64-is1chhhu/src/drm-sys-0.7.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 4135,
    "crate": "drm-sys",
    "version": "0.7.0",
    "crate_id": "8741",
    "version_id": "1118699",
    "downloads": 1958647,
    "cumulative_downloads": 110012392937,
    "cumulative_share_of_global": 0.4113109401907927,
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
