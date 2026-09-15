# `drm-sys` `0.7.0`

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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
    "/target/debug/build/drm-sys-1e3689cce830f247",
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
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1058073-1783999227154547207.map",
  "pid": 1058073,
  "ppid": 1058041,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1058073-1783999227154547207.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "workspace_root": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "cargo_args": [
    "build",
    "--target",
    "aarch64-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
      "name": "drm-sys",
      "version": "0.7.0",
      "manifest_path": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0"
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
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 1058073,
  "ppid": 1058041,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:c194cb3b9a979006:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
  "pid": 1058073,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:994a9e67901952c2:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "02f56fb25be205550773fec22314591c47ba0e3f06c934b1997cad71d4179c6f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:59f92a86a104ecdd:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "605c5205a9fad53da29fb2480e9d2f9bd38e0a76f8577cacccc78c6f116ea7f6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:539e83e7cce87d64:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "6fc57aad748ae3a5e28b6f2f1e989a240ef3552e6442ec4dab5c248e46d4c1f2",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:0851a153298cbee5:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "3d16c23ac5cf875481ebfde4d8c152411dfd4cffbda9af19345bab7a3b3c4c63",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:970c3bdeaa052dba:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "34dcd7518b652f6193eae85cd2ce670a055c0e81dbbaf39401dd9fe6fa50e74a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "used:cc:62dfcae9fb1d3736:1485e6cdc03ac574:abadaea9e2cabc36",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
  "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
  "pid": 1058073,
  "sha256": "da6811dae70cb6083d2767cac1d18d10434f5e6665ae78c6c23e6f8961e7e65d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cargo_manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "cargo_pkg_name": "drm-sys",
  "cargo_pkg_version": "0.7.0",
  "context_path": "/tmp/native-trace-1057530-1783999224223/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-1057530-1783999224223/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 1058073,
  "ppid": 1058041,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
    "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
    "/target/debug/build/drm-sys-1e3689cce830f247",
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
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
      "kind": "object",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-1058073-1783999227154547207.map",
  "pid": 1058073,
  "ppid": 1058041,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-1058073-1783999227154547207.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
  "parsed_event_count": 923,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 924,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n14.387  cc               1062826 1062825   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcLozdds/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n14.409  rustc            1062833 1062810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.427  rustc            1062839 1062810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.441  collect2         1062831 1062826   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.445  ld.lld           1062844 1062831   0 \n14.447  rust-lld         1062844 1062831   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.560  execsnoop        1062864 1062789   0 /usr/local/bin/execsnoop -t\n14.561  python3          1062864 1062789   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.609  build-script-bu  1062883 1062716   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n14.624  rustc            1062886 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n14.629  cc               1062887 1062791   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustc44Nxpc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc44Nxpc/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustc44Nxpc/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n14.632  cc               1062888 1062887   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc44Nxpc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc44Nxpc/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustc44Nxpc/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n14.642  collect2         1062892 1062888   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc44Nxpc/raw-dylibs ...\n14.642  ld.lld           1062893 1062892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc44Nxpc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n14.646  rust-lld         1062893 1062892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n14.917  rustc            1062936 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.924  rustc            1062937 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk_derives --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk_derives-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.929  rustc            1062938 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk_proc_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk_proc_macros-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.990  cc               1062951 1062802   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustc7dWqxR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7dWqxR/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustc7dWqxR/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n14.994  cc               1062953 1062951   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc7dWqxR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7dWqxR/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustc7dWqxR/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.002  collect2         1062954 1062953   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc7dWqxR/raw-dylibs ...\n15.005  ld.lld           1062955 1062954   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc7dWqxR/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.009  rust-lld         1062955 1062954   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.151  rustc            1062985 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"default\" --cfg ...\n15.241  cc               1062995 1062938   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcQnKJKQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcQnKJKQ/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustcQnKJKQ/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n15.243  cc               1062996 1062995   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcQnKJKQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcQnKJKQ/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustcQnKJKQ/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n15.248  collect2         1062997 1062996   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcQnKJKQ/raw-dylibs ...\n15.253  ld.lld           1062998 1062997   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcQnKJKQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.256  rust-lld         1062998 1062997   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.323  cc               1063018 1062937   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcbQu2SI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbQu2SI/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustcbQu2SI/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.328  cc               1063022 1063018   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcbQu2SI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbQu2SI/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustcbQu2SI/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.334  collect2         1063023 1063022   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcbQu2SI/raw-dylibs ...\n15.337  ld.lld           1063024 1063023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcbQu2SI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.339  rust-lld         1063024 1063023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.402  rustc            1063045 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n15.744  rustc            1063093 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n15.829  cc               1063112 1062799   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n15.831  cc               1063113 1063112   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n15.835  collect2         1063115 1063113   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs ...\n15.838  ld.lld           1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.841  rust-lld         1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.886  rustc            1063136 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n15.957  cc               1063159 1063136   0 /tmp/native-trace-1061857-1783999237062/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n15.960  cc               1063161 1063159   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n15.965  collect2         1063162 1063161   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.968  ld.lld           1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n15.973  rust-lld         1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.084  rustc            1063190 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=480ed063e9b929e7 ...\n16.105  build-script-bu  1063196 1062716   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n16.107  aarch64-linux-g  1063197 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family\n16.109  cc1              1063198 1063197   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.114  aarch64-linux-g  1063203 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.116  aarch64-linux-g  1063204 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil\n16.118  cc1              1063205 1063204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.123  aarch64-linux-g  1063206 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.126  aarch64-linux-g  1063207 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -c /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c\n16.127  cc1              1063209 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c -quiet -dumpbase flag_check.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -O0 -Wall -Wextra -Wno-unused-value -ffunction-sections -fdata-sections -fPIC -fasynchronous-unwind-tables ...\n16.138  as               1063211 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check /tmp/ccshdZxV.s\n16.148  aarch64-linux-g  1063212 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -c src/parser.c\n16.150  cc1              1063213 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/parser.c -quiet -dumpbase parser.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n16.236  cc               1063218 1062936   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n16.237  cc               1063219 1063218   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n16.240  collect2         1063220 1063219   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs ...\n16.241  ld.lld           1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.242  rust-lld         1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.373  rustc            1063239 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0fb8ee0bf7492b0e ...\n17.317  rustc            1063282 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.399  cc               1063294 1063282   0 /tmp/native-trace-1057733-1783999224707/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.400  cc               1063295 1063294   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.403  collect2         1063296 1063295   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.404  ld.lld           1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n17.405  rust-lld         1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.454  build-script-bu  1063315 1058460   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n17.459  rustc            1063317 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.506  rustc            1063322 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.588  cc               1063333 1063322   0 /tmp/native-trace-1057721-1783999224654/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.589  cc               1063334 1063333   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.593  collect2         1063335 1063334   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.594  ld.lld           1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n17.596  rust-lld         1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.650  build-script-bu  1063354 1058268   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n17.658  rustc            1063356 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.662  cargo            1063357 1062789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.674  rustc            1063361 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.694  rustc            1063371 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n17.695  rustc            1063369 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n17.695  rustc            1063370 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n17.737  cc               1063384 1063370   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n17.738  cc               1063385 1063384   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n17.740  collect2         1063386 1063385   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.742  ld.lld           1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n17.743  rust-lld         1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.769  rustc            1063410 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n17.780  build-script-bu  1063415 1063357   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n17.784  rustc            1063417 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 1058137,
  "build_script_target_dir": "drm-sys-1e3689cce830f247",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
  "pid": 1058137,
  "ppid": 1058032,
  "root_cargo_pid": 1058032,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "_build_script_manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "_build_script_out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out"
}
```

#### Record 16

```json
{
  "crate": "drm-sys",
  "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "event_id": "bsrun:a5f846bf4603a4e2:fc545b1ff076f511:750ef5a1d5bc27c7",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
  "out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out",
  "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
  "success": true,
  "target": null,
  "version": "0.7.0",
  "_owner": {
    "crate": "drm-sys",
    "version": "0.7.0",
    "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
    "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T03:20:50.253480+00:00",
  "crate": "drm-sys",
  "version": "0.7.0",
  "architecture": "aarch64",
  "duration_seconds": 32.34541700966656,
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
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "manifest_path": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0/Cargo.toml"
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "workspace_root": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "cargo_args": [
        "build",
        "--target",
        "aarch64-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
          "name": "drm-sys",
          "version": "0.7.0",
          "manifest_path": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0"
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
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 1058073,
      "ppid": 1058041,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:c194cb3b9a979006:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
      "pid": 1058073,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:994a9e67901952c2:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "02f56fb25be205550773fec22314591c47ba0e3f06c934b1997cad71d4179c6f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:59f92a86a104ecdd:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "605c5205a9fad53da29fb2480e9d2f9bd38e0a76f8577cacccc78c6f116ea7f6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:539e83e7cce87d64:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "6fc57aad748ae3a5e28b6f2f1e989a240ef3552e6442ec4dab5c248e46d4c1f2",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:0851a153298cbee5:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "3d16c23ac5cf875481ebfde4d8c152411dfd4cffbda9af19345bab7a3b3c4c63",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:970c3bdeaa052dba:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "34dcd7518b652f6193eae85cd2ce670a055c0e81dbbaf39401dd9fe6fa50e74a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "used:cc:62dfcae9fb1d3736:1485e6cdc03ac574:abadaea9e2cabc36",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247",
      "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
      "pid": 1058073,
      "sha256": "da6811dae70cb6083d2767cac1d18d10434f5e6665ae78c6c23e6f8961e7e65d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cargo_manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "cargo_pkg_name": "drm-sys",
      "cargo_pkg_version": "0.7.0",
      "context_path": "/tmp/native-trace-1057530-1783999224223/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-1057530-1783999224223/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 1058073,
      "ppid": 1058041,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
        "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/raw-dylibs",
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
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
        "/target/debug/build/drm-sys-1e3689cce830f247",
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
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/rustcL4FNmC/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.3dp7d9ifwckq0uq5qz5g618h1.0cst9v4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.54kwwd04mm512vh8w6umjt6ts.0cst9v4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.6s50eqv4qxrdmkx5argwc2w5g.0cst9v4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.8xsee3k5xur2h5ag2monw1ser.0cst9v4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.91qtc13cmmgjh4wkprfz6hbf0.0cst9v4.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-sys-1e3689cce830f247",
          "kind": "object",
          "path": "/target/debug/build/drm-sys-1e3689cce830f247/build_script_build-1e3689cce830f247.0fwfbhcmc72gscdjvzcydzdco.0cst9v4.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-1058073-1783999227154547207.map",
      "pid": 1058073,
      "ppid": 1058041,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-1058073-1783999227154547207.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
      "parsed_event_count": 923,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 924,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n14.387  cc               1062826 1062825   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcLozdds/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n14.409  rustc            1062833 1062810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n14.427  rustc            1062839 1062810   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n14.441  collect2         1062831 1062826   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n14.445  ld.lld           1062844 1062831   0 \n14.447  rust-lld         1062844 1062831   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ... /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGv1se5.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n14.560  execsnoop        1062864 1062789   0 /usr/local/bin/execsnoop -t\n14.561  python3          1062864 1062789   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.609  build-script-bu  1062883 1062716   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n14.624  rustc            1062886 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n14.629  cc               1062887 1062791   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustc44Nxpc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc44Nxpc/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustc44Nxpc/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n14.632  cc               1062888 1062887   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc44Nxpc/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc44Nxpc/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustc44Nxpc/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n14.642  collect2         1062892 1062888   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc44Nxpc/raw-dylibs ...\n14.642  ld.lld           1062893 1062892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc44Nxpc/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n14.646  rust-lld         1062893 1062892   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccejLq3J.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n14.917  rustc            1062936 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror_impl --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-impl-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.924  rustc            1062937 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk_derives --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk_derives-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.929  rustc            1062938 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk_proc_macros --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk_proc_macros-0.1.5/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n14.990  cc               1062951 1062802   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustc7dWqxR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7dWqxR/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustc7dWqxR/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n14.994  cc               1062953 1062951   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc7dWqxR/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc7dWqxR/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustc7dWqxR/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.002  collect2         1062954 1062953   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc7dWqxR/raw-dylibs ...\n15.005  ld.lld           1062955 1062954   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustc7dWqxR/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.009  rust-lld         1062955 1062954   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccd3LuWm.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.151  rustc            1062985 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-1.13.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"default\" --cfg ...\n15.241  cc               1062995 1062938   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcQnKJKQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcQnKJKQ/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustcQnKJKQ/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n15.243  cc               1062996 1062995   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcQnKJKQ/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcQnKJKQ/symbols.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.frunk_proc_macros.13c3a7c4de93cf17-cgu.0.rcgu.o /target/debug/deps/rustcQnKJKQ/rmeta.o /target/debug/deps/frunk_proc_macros-e396acbea1a66f70.bihknfxedxswgd7ejp29dyisw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n15.248  collect2         1062997 1062996   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcQnKJKQ/raw-dylibs ...\n15.253  ld.lld           1062998 1062997   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcQnKJKQ/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.256  rust-lld         1062998 1062997   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTk6NrX.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_proc_macros-e396acbea1a66f70.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.323  cc               1063018 1062937   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcbQu2SI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbQu2SI/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustcbQu2SI/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.328  cc               1063022 1063018   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcbQu2SI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcbQu2SI/symbols.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.0.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.1.rcgu.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.frunk_derives.afd07acc9562d681-cgu.2.rcgu.o /target/debug/deps/rustcbQu2SI/rmeta.o /target/debug/deps/frunk_derives-0e8326e89bb5dbea.ayah64f59wvecz3iqukagju1x.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libfrunk_proc_macro_helpers-858415003023552b.rlib /target/debug/deps/libsyn-2d6b0ac77b801127.rlib /target/debug/deps/libquote-5fd63f231ce71c57.rlib /target/debug/deps/libproc_macro2-beac2d766ec0e362.rlib /target/debug/deps/libunicode_ident-2a4577d1de655b9f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /target/debug/deps/libfrunk_core-3bcb85253d012446.rlib ...\n15.334  collect2         1063023 1063022   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcbQu2SI/raw-dylibs ...\n15.337  ld.lld           1063024 1063023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcbQu2SI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.339  rust-lld         1063024 1063023   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccW9IhDV.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libfrunk_derives-0e8326e89bb5dbea.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n15.402  rustc            1063045 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n15.744  rustc            1063093 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name frunk --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/frunk-0.4.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"default\" --cfg feature=\"frunk_proc_macros\" ...\n15.829  cc               1063112 1062799   0 /tmp/native-trace-1057733-1783999224707/shims/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n15.831  cc               1063113 1063112   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcHnhVtI/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcHnhVtI/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n15.835  collect2         1063115 1063113   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs ...\n15.838  ld.lld           1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcHnhVtI/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n15.841  rust-lld         1063116 1063115   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccYZ5IZO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n15.886  rustc            1063136 1062716   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 bindings/rust/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=ea5f6c407316a73b ...\n15.957  cc               1063159 1063136   0 /tmp/native-trace-1061857-1783999237062/shims/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n15.960  cc               1063161 1063159   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/rustc8lYsQD/symbols.o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.08ix9m27ecj28epu70w4cglga.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.1lc1abcorsumvsogfxkik9p45.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2l3b79viwz29x35q98iknkmow.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.2n7qjvq3h4l1twg1oz5rjfz17.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4ppt6ynrtus2y7ladjn1q0s7r.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.4zqkvs7gpw6qfg4x16miqqhci.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5kmhh0lq4p6b1zesrvaal5rt7.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.7t8j1zf2deqctroe7cyg6gro1.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.e5t21bxcgq7ct6e9nlj3oayej.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.elad7io2sdtq1538n8pr70b49.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.f1e6opguctbwzy6uif0fse7yk.0g6jbut.r /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201.5za94si9f93pzwcvsyazp9xtu.0g6jbut.r -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib ...\n15.965  collect2         1063162 1063161   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.968  ld.lld           1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build_script_build-d38dba320c63e201 ...\n15.973  rust-lld         1063163 1063162   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqsshXp.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.084  rustc            1063190 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=480ed063e9b929e7 ...\n16.105  build-script-bu  1063196 1062716   0 /target/debug/build/tree-sitter-c-sharp-d38dba320c63e201/build-script-build\n16.107  aarch64-linux-g  1063197 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family\n16.109  cc1              1063198 1063197   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/2950616675275674650detect_compiler_family -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.114  aarch64-linux-g  1063203 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.116  aarch64-linux-g  1063204 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil\n16.118  cc1              1063205 1063204   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/16021399883272081461detect_compiler_famil -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.123  aarch64-linux-g  1063206 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.126  aarch64-linux-g  1063207 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -c /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c\n16.127  cc1              1063209 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check.c -quiet -dumpbase flag_check.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check -O0 -Wall -Wextra -Wno-unused-value -ffunction-sections -fdata-sections -fPIC -fasynchronous-unwind-tables ...\n16.138  as               1063211 1063207   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -EL -mabi=lp64 -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/flag_check /tmp/ccshdZxV.s\n16.148  aarch64-linux-g  1063212 1063196   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -std=c11 -I src -Wall -Wextra -Wno-unused-value -o /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -c src/parser.c\n16.150  cc1              1063213 1063212   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I src -imultiarch aarch64-linux-gnu src/parser.c -quiet -dumpbase parser.c -mlittle-endian -mabi=lp64 -auxbase-strip /target/aarch64-unknown-linux-gnu/debug/build/tree-sitter-c-sharp-d1c4553b8f5507e9/out/ea708c7824d36062-parser.o -g -gdwarf-4 -O0 -Wall -Wextra -Wno-unused-value ...\n16.236  cc               1063218 1062936   0 /tmp/native-trace-1057721-1783999224654/shims/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n16.237  cc               1063219 1063218   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcqsXPOX/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcqsXPOX/symbols.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.00.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.01.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.02.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.03.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.04.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.05.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.06.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.07.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.08.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.09.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.10.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.11.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.12.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.13.rcgu.o /target/debug/deps/thiserror_impl-9a9c93b01c16943a.thiserror_impl.156b84df1a0c1846-cgu.14.rcgu.o ...\n16.240  collect2         1063220 1063219   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs ...\n16.241  ld.lld           1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustcqsXPOX/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n16.242  rust-lld         1063221 1063220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccqR4XtP.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libthiserror_impl-9a9c93b01c16943a.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n16.373  rustc            1063239 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name thiserror --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/thiserror-1.0.69/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=0fb8ee0bf7492b0e ...\n17.317  rustc            1063282 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.399  cc               1063294 1063282   0 /tmp/native-trace-1057733-1783999224707/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.400  cc               1063295 1063294   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustcJvCwlO/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.10mw4w3.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.10mw4w3.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.403  collect2         1063296 1063295   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.404  ld.lld           1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n17.405  rust-lld         1063297 1063296   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWaqIH2.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.454  build-script-bu  1063315 1058460   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n17.459  rustc            1063317 1058460   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.506  rustc            1063322 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.588  cc               1063333 1063322   0 /tmp/native-trace-1057721-1783999224654/shims/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.589  cc               1063334 1063333   0 /usr/bin/cc -m64 /target/debug/build/mysql_common-0a41ad95518e6d02/rustc0wPbum/symbols.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.445jveqfgquo3yj4aykevnpks.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.5iu6d8hahadxqgm0l710i2zl0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.7ljrr021f2klui4vctyu6lan0.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.bqyruvzjnp0goo898mbteo1fh.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.e40a14vcb2yww6o7d5cr43dii.1cx8bt5.rcgu.o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02.55nk8vtse4uq4q3vs5gd1sogr.1cx8bt5.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsubprocess-860a00b0d486aaab.rlib /target/debug/deps/libcmake-ee8b23b47bb2c1c1.rlib /target/debug/deps/libcc-7fea9c8da0fe21a4.rlib /target/debug/deps/libfind_msvc_tools-60e3732174de9068.rlib /target/debug/deps/libshlex-f2fa52250b1d670f.rlib /target/debug/deps/libbindgen-71e1a39506d794b8.rlib /target/debug/deps/libshlex-9d2fae39757f538b.rlib /target/debug/deps/librustc_hash-4dbfd48eacc1fe41.rlib /target/debug/deps/libregex-5b2c43976b4127e6.rlib ...\n17.593  collect2         1063335 1063334   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.594  ld.lld           1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/mysql_common-0a41ad95518e6d02/build_script_build-0a41ad95518e6d02 ...\n17.596  rust-lld         1063336 1063335   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4Yn25y.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.650  build-script-bu  1063354 1058268   0 /target/debug/build/mysql_common-0a41ad95518e6d02/build-script-build\n17.658  rustc            1063356 1058268   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name mysql_common --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"bigdecimal03\" --cfg feature=\"default\" --cfg feature=\"frunk\" ...\n17.662  cargo            1063357 1062789   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n17.674  rustc            1063361 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n17.694  rustc            1063371 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name shlex --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=unexpected_cfgs --check-cfg cfg(manual_codegen_check) --cfg feature=\"default\" --cfg ...\n17.695  rustc            1063369 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name find_msvc_tools --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n17.695  rustc            1063370 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n17.737  cc               1063384 1063370   0 /tmp/native-trace-1062789-1783999241328/shims/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n17.738  cc               1063385 1063384   0 /usr/bin/cc -m64 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/rustcuW3uX1/symbols.o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.build_script_build.3e123942ba959b6 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2.0q2hrwea9j9x0ytuhd3euhwix.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n17.740  collect2         1063386 1063385   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n17.742  ld.lld           1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build_script_build-04f523abf8aa8aa2 ...\n17.743  rust-lld         1063387 1063386   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccaHGIOT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n17.769  rustc            1063410 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name cc --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(disable_clang_cl_tests) --check-cfg cfg(docsrs,test) --check-cfg ...\n17.780  build-script-bu  1063415 1063357   0 /target/debug/build/tree-sitter-language-04f523abf8aa8aa2/build-script-build\n17.784  rustc            1063417 1063357   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name tree_sitter_language --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/tree-sitter-language-0.1.7/src/language.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --warn=clippy::pedantic --warn=clippy::nursery --warn=clippy::cargo --allow=clippy::used_underscore_items --allow=clippy::unused_self --allow=clippy::unnecessary_wraps ...\n"
    },
    {
      "argv": [
        "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 1058137,
      "build_script_target_dir": "drm-sys-1e3689cce830f247",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
      "pid": 1058137,
      "ppid": 1058032,
      "root_cargo_pid": 1058032,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "drm-sys",
      "cwd": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "event_id": "bsrun:a5f846bf4603a4e2:fc545b1ff076f511:750ef5a1d5bc27c7",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/drm-sys-1e3689cce830f247/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
      "out_dir": "/target/debug/build/drm-sys-1e3689cce830f247/out",
      "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
      "success": true,
      "target": null,
      "version": "0.7.0",
      "_owner": {
        "crate": "drm-sys",
        "version": "0.7.0",
        "package_id": "path+file:///tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0#drm-sys@0.7.0",
        "manifest_dir": "/tmp/crate-build-aarch64-haf8upwf/src/drm-sys-0.7.0",
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
