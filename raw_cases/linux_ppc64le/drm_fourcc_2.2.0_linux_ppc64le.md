# `drm-fourcc` `2.2.0`

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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
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
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
    "/target/debug/build/drm-fourcc-13ade45021069b5d",
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
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-783676-1783996868358635691.map",
  "pid": 783676,
  "ppid": 783664,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-783676-1783996868358635691.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "workspace_root": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0"
  ],
  "packages": [
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
      "name": "drm-fourcc",
      "version": "2.2.0",
      "manifest_path": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0"
    }
  ],
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "exit_code": 0,
  "kind": "exec",
  "pid": 783676,
  "ppid": 783664,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:11291e1b6b14ddb7:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
  "pid": 783676,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:b655425c57b6a391:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "be8845e4ce6810310eceb7878117c5903d17b4f304e0f547b8489f8ceab69b8d",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:b7d437dd7f27db73:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "972e551a193c988f2c3d50a1b9382bc0c2454f3a295a8a01af36b76f8d947e4b",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:00be9534adfb5f83:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "74cfa865381bb7021d94a13f69f924b13fee53e36d6d2a8c2f86fbdceff6d62a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:8b0cc5546b0243b2:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "c04ae20c687fd3953d5cf5dbacea0456ccb99b2902b6ece3ae49158fe138aa75",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:5b81f2041fbb938b:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "ee4e45c0dce2f4ebac46568a7b65d54729f81050b6a32a55791e52daac692866",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:e36cf8ce80b6cda1:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "f5275b918439dc854deb8a15ab89595c26e79dd10182519b39cb27e6cf6bbade",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "used:cc:d5484282d1bb58d2:6b453fef01abc38a:4d3e055c7e61eb52",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
  "pid": 783676,
  "sha256": "95478e9f313919749166b172c558525439c91a2274761572bd659f7c177df3ca",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
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
  "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "cargo_pkg_name": "drm-fourcc",
  "cargo_pkg_version": "2.2.0",
  "context_path": "/tmp/native-trace-783002-1783996865542/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-783002-1783996865542/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 783676,
  "ppid": 783664,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
    "/target/debug/build/drm-fourcc-13ade45021069b5d",
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
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
      "kind": "object",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-783676-1783996868358635691.map",
  "pid": 783676,
  "ppid": 783664,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-783676-1783996868358635691.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
  "parsed_event_count": 344,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 345,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "47d5f79a22 ...\n6.702   aarch64-linux-g  785005 625892   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/libwasm-opt-cc.a /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-Twine.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-UnicodeCaseFold.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-WithColor.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-YAMLParser.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-YAMLTraits.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/4897f73433348714-LLVMDwarf.o\n7.493   runc             785006 776968   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 --log-format json --systemd-cgroup kill --all 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f 9\n7.511   runc             785012 776968   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 --log-format json --systemd-cgroup delete 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f\n7.704   containerd-shim  785019 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 delete\n7.706   runc             785025 785019   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148 --log-format json delete --force 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f\n7.747   sh               785035 785032   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth72f43b4\n7.748   ethtool          785036 785035   0 /usr/sbin/ethtool -i veth72f43b4\n7.748   sed              785037 785035   0 /usr/bin/sed -n s/^driver: //p\n7.754   systemd-sysctl   785040 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth72f43b4 --prefix=/net/ipv4/neigh/veth72f43b4 --prefix=/net/ipv6/conf/veth72f43b4 --prefix=/net/ipv6/neigh/veth72f43b4\n8.125   aarch64-linux-g  785043 625892   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/libwasm-opt-cc.a\n8.226   cross            785044 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n8.228   rustc            785047 785044   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.233   rustc            785047 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.244   rustc            785059 785044   0 /home/xmoe/.cargo/bin/rustc -vV\n8.250   rustc            785059 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.261   cargo            785069 785044   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.266   cargo            785069 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.276   rustc            785078 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.286   rustc            785080 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.297   rustc            785084 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.403   rustc            785089 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.427   rustc            785091 785044   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.432   rustc            785091 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.444   docker           785103 785044   0 /usr/bin/docker --help\n8.458   docker           785116 785044   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.459   cross            785117 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n8.461   rustc            785121 785117   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.466   rustc            785121 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.472   runc             785138 1599     0 /usr/bin/runc --version\n8.475   docker-init      785144 1599     0 /usr/bin/docker-init --version\n8.476   docker           785147 785044   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.481   rustc            785154 785117   0 /home/xmoe/.cargo/bin/rustc -vV\n8.487   rustc            785154 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.489   runc             785167 1599     0 /usr/bin/runc --version\n8.493   docker-init      785173 1599     0 /usr/bin/docker-init --version\n8.497   cargo            785175 785117   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n8.503   cargo            785175 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n8.514   rustc            785184 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.518   rustup           785185 785044   0 /home/xmoe/.cargo/bin/rustup toolchain list\n8.524   rustup           785195 785044   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.525   rustc            785196 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.537   rustc            785208 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.548   rustup           785212 785044   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.573   uname            785222 785044   0 /usr/bin/uname -r\n8.591   docker           785223 785044   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.632   systemd-sysctl   785236 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae4cc8f --prefix=/net/ipv4/neigh/vethae4cc8f --prefix=/net/ipv6/conf/vethae4cc8f --prefix=/net/ipv6/neigh/vethae4cc8f\n8.632   systemd-sysctl   785237 785042   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc418ad2 --prefix=/net/ipv4/neigh/vethc418ad2 --prefix=/net/ipv6/conf/vethc418ad2 --prefix=/net/ipv6/neigh/vethc418ad2\n8.639   rustc            785242 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.649   containerd-shim  785268 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 start\n8.655   containerd-shim  785276 785268   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 -address /var/run/docker/containerd/containerd.sock\n8.659   runc             785285 785276   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976\n8.666   exe              785292 785285   0 /proc/self/exe init\n8.668   rustc            785295 785117   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.674   rustc            785295 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.686   docker           785315 785117   0 /usr/bin/docker --help\n8.694   exe              785325 785285   0 /proc/1599/exe -exec-root=/var/run/docker 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 d7da31e8f8e1\n8.699   docker           785331 785117   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.713   runc             785344 1599     0 /usr/bin/runc --version\n8.716   docker-init      785350 1599     0 /usr/bin/docker-init --version\n8.718   docker           785352 785117   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.724   exe              785358 1599     0 /proc/self/exe /var/run/docker/netns/34fb38092dc7 all false\n8.730   runc             785369 1599     0 /usr/bin/runc --version\n8.735   docker-init      785378 1599     0 /usr/bin/docker-init --version\n8.758   rustup           785389 785117   0 /home/xmoe/.cargo/bin/rustup toolchain list\n8.765   rustup           785398 785117   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.771   runc             785409 785276   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --log-format json --systemd-cgroup start 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976\n8.777   sh               785305 785276   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n8.778   cargo            785415 785305   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n8.789   cargo-native-tr  785415 785305   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n8.791   rustup           785416 785117   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.793   cargo            785417 785415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n8.804   rustc            785426 785417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.816   rustc            785428 785417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.817   uname            785429 785117   0 /usr/bin/uname -r\n8.835   execsnoop        785433 785415   0 /usr/local/bin/execsnoop -t\n8.836   python3          785433 785415   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n8.836   docker           785435 785117   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.892   systemd-sysctl   785449 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0e407b8 --prefix=/net/ipv4/neigh/veth0e407b8 --prefix=/net/ipv6/conf/veth0e407b8 --prefix=/net/ipv6/neigh/veth0e407b8\n8.892   systemd-sysctl   785450 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b58c63 --prefix=/net/ipv4/neigh/veth7b58c63 --prefix=/net/ipv6/conf/veth7b58c63 --prefix=/net/ipv6/neigh/veth7b58c63\n8.910   containerd-shim  785451 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 start\n8.914   containerd-shim  785457 785451   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 -address /var/run/docker/containerd/containerd.sock\n8.918   runc             785469 785457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257\n8.924   exe              785476 785469   0 /proc/self/exe init\n8.956   exe              785486 785469   0 /proc/1599/exe -exec-root=/var/run/docker a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 d7da31e8f8e1\n8.982   exe              785494 1599     0 /proc/self/exe /var/run/docker/netns/7e1ad96c9bc5 all false\n9.037   runc             785511 785457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --log-format json --systemd-cgroup start a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257\n9.043   sh               785480 785457   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.044   cargo            785517 785480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n9.056   cargo-native-tr  785517 785480   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n9.059   cargo            785518 785517   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.071   rustc            785519 785518   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.084   rustc            785521 785518   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.102   execsnoop        785525 785517   0 /usr/local/bin/execsnoop -t\n9.103   python3          785525 785517   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.673   rustc            785529 617400   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasm_opt_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"dwarf\" --check-cfg cfg(docsrs,test) ...\n11.067  runc             785599 778816   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac --log-format json --systemd-cgroup kill --all 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2 9\n11.086  runc             785606 778816   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac --log-format json --systemd-cgroup delete 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2\n11.090  cargo            785612 785517   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n11.104  rustc            785613 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.128  rustc            785621 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=2dfde9935a2aa7cd ...\n11.128  rustc            785623 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=200e81327dd5a365 ...\n11.128  rustc            785625 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.128  rustc            785624 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=16b048854222583a ...\n11.173  cargo            785643 785415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n11.187  rustc            785650 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.215  rustc            785703 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.216  rustc            785699 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=2dfde9935a2aa7cd ...\n11.217  rustc            785702 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=200e81327dd5a365 ...\n11.217  rustc            785700 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=33bc0340c044253b ...\n11.228  cc               785708 785625   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustc7cU5ey/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.1mwjg9t.rc ...\n11.230  cc               785722 785708   0 /usr/bin/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustc7cU5ey/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.1mwjg9t.rc ...\n11.232  cc               785721 785623   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcgakjC3/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.234  cc               785723 785721   0 /usr/bin/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcgakjC3/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.235  collect2         785724 785722   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  collect2         785726 785723   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  ld.lld           785725 785724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c ...\n11.239  rust-lld         785725 785724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.242  ld.lld           785728 785726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7 ...\n11.245  cc               785727 785621   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcldIRtN/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.245  rust-lld         785728 785726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.246  cc               785729 785727   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcldIRtN/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.250  collect2         785730 785729   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.252  ld.lld           785731 785730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9 ...\n11.254  rust-lld         785731 785730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.281  containerd-shim  785789 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac delete\n11.285  runc             785800 785789   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f --log-format json delete --force 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2\n11.312  build-script-bu  785850 785612   0 /target/debug/build/quote-5ea12905e6b8e2d7/build-script-build\n11.314  rustc            785851 785850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.319  build-script-bu  785854 785612   0 /target/debug/build/proc-macro2-eca720657268f2c9/build-script-build\n11.323  rustc            785857 785854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.324  cc               785856 785703   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustcKNz22k/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.0hbv40a.rc ...\n11.324  sh               785858 785265   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf4dd7b0\n11.328  sed              785862 785858   0 \n11.328  cc               785860 785856   0 /usr/bin/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustcKNz22k/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.0hbv40a.rc ...\n11.328  ethtool          785861 785858   0 /usr/sbin/ethtool -i vethf4dd7b0\n11.332  collect2         785865 785860   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.334  ld.lld           785867 785865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c ...\n11.336  systemd-sysctl   785868 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4dd7b0 --prefix=/net/ipv4/neigh/vethf4dd7b0 --prefix=/net/ipv6/conf/vethf4dd7b0 --prefix=/net/ipv6/neigh/vethf4dd7b0\n11.336  rust-lld         785867 785865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.336  build-script-bu  785871 785612   0 /target/debug/build/proc-macro-warning-ad4748846f063e1c/build-script-build\n11.342  cc               785873 785702   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcymUPvd/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.343  rustc            785872 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=62b3a44cd46fff0e ...\n11.345  cc               785874 785873   0 /usr/bin/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcymUPvd/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.348  collect2         785875 785874   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.349  ld.lld           785876 785875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7 ...\n11.351  rust-lld         785876 785875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.353  cc               785877 785699   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcO4x7hI/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.355  cc               785894 785877   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcO4x7hI/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.357  collect2         785898 785894   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.359  ld.lld           785899 785898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9 ...\n11.361  rust-lld         785899 785898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.404  build-script-bu  785933 785643   0 /target/debug/build/quote-5ea12905e6b8e2d7/build-script-build\n11.407  rustc            785934 785933   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.409  build-script-bu  785936 785643   0 /target/debug/build/proc-macro2-eca720657268f2c9/build-script-build\n11.411  rustc            785937 785936   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.415  build-script-bu  785939 785643   0 /target/debug/build/proc-macro-warning-ad4748846f063e1c/build-script-build\n11.425  rustc            785943 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=f80382781c4ff649 ...\n11.524  rustc            785951 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=13b38aede1a377aa ...\n11.524  rustc            785952 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clone-impls\", \"default\", \"derive\", \"extra-traits\", \"fold\", \"full\", \"parsing\", \"printing\", \"proc-macro\", \"te -C metadata=cc2ee696bc0cfdb9 ...\n11.607  rustc            785970 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clone-impls\", \"default\", \"derive\", \"extra-traits\", \"fold\", \"full\", \"parsing\", \"printing\", \"proc-macro\", \"te -C metadata=63304be103d3cbfe ...\n11.607  rustc            785969 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=9ab743b18e379101 ...\n11.759  rustc            785991 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_warning --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.840  rustc            786003 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_warning --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n13.495  systemd-userwor  786175 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n13.496  systemd-userwor  786176 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n13.745  runc             786177 768912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 --log-format json --systemd-cgroup kill --all 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5 9\n13.763  runc             786183 768912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 --log-format json --systemd-cgroup delete 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5\n13.972  containerd-shim  786190 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 delete\n13.975  runc             786197 786190   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b --log-format json delete --force 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5\n14.016  systemd-sysctl   786202 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha0a999b --prefix=/net/ipv4/neigh/vetha0a999b --prefix=/net/ipv6/conf/vetha0a999b --prefix=/net/ipv6/neigh/vetha0a999b\n"
}
```

#### Record 16

```json
{
  "argv": [
    "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 783710,
  "build_script_target_dir": "drm-fourcc-13ade45021069b5d",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build",
  "pid": 783710,
  "ppid": 783657,
  "root_cargo_pid": 783657,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "_build_script_out_dir": "/target/debug/build/drm-fourcc-13ade45021069b5d/out"
}
```

#### Record 17

```json
{
  "crate": "drm-fourcc",
  "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "event_id": "bsrun:cce3d159f9dd8e33:2e5c452816fbab5c:eb734493b5afb56f",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
  "out_dir": "/target/debug/build/drm-fourcc-13ade45021069b5d/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
  "success": true,
  "target": null,
  "version": "2.2.0",
  "_owner": {
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
    "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:41:30.995087+00:00",
  "crate": "drm-fourcc",
  "version": "2.2.0",
  "architecture": "ppc64le",
  "duration_seconds": 28.58648066688329,
  "trace_record_count": 17,
  "trace_owner_summary": {
    "owner_package_count": 1,
    "owner_packages": [
      {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "manifest_path": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0/Cargo.toml"
      }
    ],
    "attributed_event_count": 14,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "drm-fourcc",
        "version": "2.2.0",
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
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "workspace_root": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0"
      ],
      "packages": [
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
          "name": "drm-fourcc",
          "version": "2.2.0",
          "manifest_path": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0"
        }
      ],
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "exit_code": 0,
      "kind": "exec",
      "pid": 783676,
      "ppid": 783664,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:11291e1b6b14ddb7:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
      "pid": 783676,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:b655425c57b6a391:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "be8845e4ce6810310eceb7878117c5903d17b4f304e0f547b8489f8ceab69b8d",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:b7d437dd7f27db73:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "972e551a193c988f2c3d50a1b9382bc0c2454f3a295a8a01af36b76f8d947e4b",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:00be9534adfb5f83:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "74cfa865381bb7021d94a13f69f924b13fee53e36d6d2a8c2f86fbdceff6d62a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:8b0cc5546b0243b2:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "c04ae20c687fd3953d5cf5dbacea0456ccb99b2902b6ece3ae49158fe138aa75",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:5b81f2041fbb938b:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "ee4e45c0dce2f4ebac46568a7b65d54729f81050b6a32a55791e52daac692866",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:e36cf8ce80b6cda1:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "f5275b918439dc854deb8a15ab89595c26e79dd10182519b39cb27e6cf6bbade",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "used:cc:d5484282d1bb58d2:6b453fef01abc38a:4d3e055c7e61eb52",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
      "pid": 783676,
      "sha256": "95478e9f313919749166b172c558525439c91a2274761572bd659f7c177df3ca",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
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
      "output": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "cargo_pkg_name": "drm-fourcc",
      "cargo_pkg_version": "2.2.0",
      "context_path": "/tmp/native-trace-783002-1783996865542/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-783002-1783996865542/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 783676,
      "ppid": 783664,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
        "/target/debug/build/drm-fourcc-13ade45021069b5d",
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
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/rustcFQRBSZ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2mgqbk4xczrl98tuox34cnk4k.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.2wwm08et4q1rfhf4zgat06ei9.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6teqihfkix5mpmwndp750zdkh.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.6vdv3kiythtj7caf45zkywej5.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.89qw7abxdxelggo0xkex9cnaf.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.c0gl9xnzuoqk9aug73cb4zkpu.00vhcd9.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/drm-fourcc-13ade45021069b5d",
          "kind": "object",
          "path": "/target/debug/build/drm-fourcc-13ade45021069b5d/build_script_build-13ade45021069b5d.5mvdrbwk8zw56ma79sdgbv8ce.00vhcd9.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-783676-1783996868358635691.map",
      "pid": 783676,
      "ppid": 783664,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-783676-1783996868358635691.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
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
      "parsed_event_count": 344,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 345,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "47d5f79a22 ...\n6.702   aarch64-linux-g  785005 625892   0 /usr/bin/aarch64-linux-gnu-ar cqD /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/libwasm-opt-cc.a /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-Twine.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-UnicodeCaseFold.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-WithColor.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-YAMLParser.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/96d45f02a8572480-YAMLTraits.o /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/4897f73433348714-LLVMDwarf.o\n7.493   runc             785006 776968   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 --log-format json --systemd-cgroup kill --all 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f 9\n7.511   runc             785012 776968   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 --log-format json --systemd-cgroup delete 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f\n7.704   containerd-shim  785019 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a69 delete\n7.706   runc             785025 785019   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148 --log-format json delete --force 7b163ff83e032fb133d6e79730ab3688ba95a391286e1a6393c18703a699148f\n7.747   sh               785035 785032   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- veth72f43b4\n7.748   ethtool          785036 785035   0 /usr/sbin/ethtool -i veth72f43b4\n7.748   sed              785037 785035   0 /usr/bin/sed -n s/^driver: //p\n7.754   systemd-sysctl   785040 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth72f43b4 --prefix=/net/ipv4/neigh/veth72f43b4 --prefix=/net/ipv6/conf/veth72f43b4 --prefix=/net/ipv6/neigh/veth72f43b4\n8.125   aarch64-linux-g  785043 625892   0 /usr/bin/aarch64-linux-gnu-ar sD /target/aarch64-unknown-linux-gnu/debug/build/wasm-opt-sys-7d07923061f74c88/out/libwasm-opt-cc.a\n8.226   cross            785044 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n8.228   rustc            785047 785044   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.233   rustc            785047 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.244   rustc            785059 785044   0 /home/xmoe/.cargo/bin/rustc -vV\n8.250   rustc            785059 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.261   cargo            785069 785044   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.266   cargo            785069 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n8.276   rustc            785078 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.286   rustc            785080 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.297   rustc            785084 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.403   rustc            785089 785069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.427   rustc            785091 785044   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.432   rustc            785091 785044   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.444   docker           785103 785044   0 /usr/bin/docker --help\n8.458   docker           785116 785044   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.459   cross            785117 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n8.461   rustc            785121 785117   0 /home/xmoe/.cargo/bin/rustc --print target-list\n8.466   rustc            785121 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n8.472   runc             785138 1599     0 /usr/bin/runc --version\n8.475   docker-init      785144 1599     0 /usr/bin/docker-init --version\n8.476   docker           785147 785044   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.481   rustc            785154 785117   0 /home/xmoe/.cargo/bin/rustc -vV\n8.487   rustc            785154 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.489   runc             785167 1599     0 /usr/bin/runc --version\n8.493   docker-init      785173 1599     0 /usr/bin/docker-init --version\n8.497   cargo            785175 785117   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n8.503   cargo            785175 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n8.514   rustc            785184 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.518   rustup           785185 785044   0 /home/xmoe/.cargo/bin/rustup toolchain list\n8.524   rustup           785195 785044   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.525   rustc            785196 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.537   rustc            785208 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n8.548   rustup           785212 785044   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.573   uname            785222 785044   0 /usr/bin/uname -r\n8.591   docker           785223 785044   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.632   systemd-sysctl   785236 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethae4cc8f --prefix=/net/ipv4/neigh/vethae4cc8f --prefix=/net/ipv6/conf/vethae4cc8f --prefix=/net/ipv6/neigh/vethae4cc8f\n8.632   systemd-sysctl   785237 785042   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc418ad2 --prefix=/net/ipv4/neigh/vethc418ad2 --prefix=/net/ipv6/conf/vethc418ad2 --prefix=/net/ipv6/neigh/vethc418ad2\n8.639   rustc            785242 785175   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.649   containerd-shim  785268 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 start\n8.655   containerd-shim  785276 785268   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 -address /var/run/docker/containerd/containerd.sock\n8.659   runc             785285 785276   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976\n8.666   exe              785292 785285   0 /proc/self/exe init\n8.668   rustc            785295 785117   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n8.674   rustc            785295 785117   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n8.686   docker           785315 785117   0 /usr/bin/docker --help\n8.694   exe              785325 785285   0 /proc/1599/exe -exec-root=/var/run/docker 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976 d7da31e8f8e1\n8.699   docker           785331 785117   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n8.713   runc             785344 1599     0 /usr/bin/runc --version\n8.716   docker-init      785350 1599     0 /usr/bin/docker-init --version\n8.718   docker           785352 785117   0 /usr/bin/docker info -f {{.SecurityOptions}}\n8.724   exe              785358 1599     0 /proc/self/exe /var/run/docker/netns/34fb38092dc7 all false\n8.730   runc             785369 1599     0 /usr/bin/runc --version\n8.735   docker-init      785378 1599     0 /usr/bin/docker-init --version\n8.758   rustup           785389 785117   0 /home/xmoe/.cargo/bin/rustup toolchain list\n8.765   rustup           785398 785117   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n8.771   runc             785409 785276   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55 --log-format json --systemd-cgroup start 3f346ad85cf61e2637621605f7e0a00fa4eec39fb05859b4c188844ed55e8976\n8.777   sh               785305 785276   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n8.778   cargo            785415 785305   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n8.789   cargo-native-tr  785415 785305   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n8.791   rustup           785416 785117   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n8.793   cargo            785417 785415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n8.804   rustc            785426 785417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n8.816   rustc            785428 785417   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n8.817   uname            785429 785117   0 /usr/bin/uname -r\n8.835   execsnoop        785433 785415   0 /usr/local/bin/execsnoop -t\n8.836   python3          785433 785415   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n8.836   docker           785435 785117   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n8.892   systemd-sysctl   785449 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth0e407b8 --prefix=/net/ipv4/neigh/veth0e407b8 --prefix=/net/ipv6/conf/veth0e407b8 --prefix=/net/ipv6/neigh/veth0e407b8\n8.892   systemd-sysctl   785450 785032   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7b58c63 --prefix=/net/ipv4/neigh/veth7b58c63 --prefix=/net/ipv6/conf/veth7b58c63 --prefix=/net/ipv6/neigh/veth7b58c63\n8.910   containerd-shim  785451 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 start\n8.914   containerd-shim  785457 785451   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 -address /var/run/docker/containerd/containerd.sock\n8.918   runc             785469 785457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257\n8.924   exe              785476 785469   0 /proc/self/exe init\n8.956   exe              785486 785469   0 /proc/1599/exe -exec-root=/var/run/docker a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257 d7da31e8f8e1\n8.982   exe              785494 1599     0 /proc/self/exe /var/run/docker/netns/7e1ad96c9bc5 all false\n9.037   runc             785511 785457   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976a --log-format json --systemd-cgroup start a5f4757f65f093617957f091c4eaf50a12db0a627e1a6e4d9f1b587976aa7257\n9.043   sh               785480 785457   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n9.044   cargo            785517 785480   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n9.056   cargo-native-tr  785517 785480   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n9.059   cargo            785518 785517   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n9.071   rustc            785519 785518   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n9.084   rustc            785521 785518   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n9.102   execsnoop        785525 785517   0 /usr/local/bin/execsnoop -t\n9.103   python3          785525 785517   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n9.673   rustc            785529 617400   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name wasm_opt_sys --edition=2018 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"dwarf\" --check-cfg cfg(docsrs,test) ...\n11.067  runc             785599 778816   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac --log-format json --systemd-cgroup kill --all 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2 9\n11.086  runc             785606 778816   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac --log-format json --systemd-cgroup delete 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2\n11.090  cargo            785612 785517   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n11.104  rustc            785613 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.128  rustc            785621 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=2dfde9935a2aa7cd ...\n11.128  rustc            785623 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=200e81327dd5a365 ...\n11.128  rustc            785625 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.128  rustc            785624 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=16b048854222583a ...\n11.173  cargo            785643 785415   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target riscv64gc-unknown-linux-gnu\n11.187  rustc            785650 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n11.215  rustc            785703 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.216  rustc            785699 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=2dfde9935a2aa7cd ...\n11.217  rustc            785702 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=200e81327dd5a365 ...\n11.217  rustc            785700 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name unicode_ident --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/unicode-ident-1.0.24/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) -C metadata=33bc0340c044253b ...\n11.228  cc               785708 785625   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustc7cU5ey/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.1mwjg9t.rc ...\n11.230  cc               785722 785708   0 /usr/bin/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustc7cU5ey/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.1mwjg9t.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.1mwjg9t.rc ...\n11.232  cc               785721 785623   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcgakjC3/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.234  cc               785723 785721   0 /usr/bin/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcgakjC3/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.235  collect2         785724 785722   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  collect2         785726 785723   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.237  ld.lld           785725 785724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c ...\n11.239  rust-lld         785725 785724   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc0Vh0BM.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.242  ld.lld           785728 785726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7 ...\n11.245  cc               785727 785621   0 /tmp/native-trace-785517-1783996877171/shims/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcldIRtN/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.245  rust-lld         785728 785726   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccwi6R9R.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.246  cc               785729 785727   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcldIRtN/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.250  collect2         785730 785729   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.252  ld.lld           785731 785730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9 ...\n11.254  rust-lld         785731 785730   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccAlWZkk.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.281  containerd-shim  785789 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac delete\n11.285  runc             785800 785789   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f --log-format json delete --force 6561902526bc17642cbeeb7adc529ea184aba4fd6b6296f0adb797790ac6d4f2\n11.312  build-script-bu  785850 785612   0 /target/debug/build/quote-5ea12905e6b8e2d7/build-script-build\n11.314  rustc            785851 785850   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.319  build-script-bu  785854 785612   0 /target/debug/build/proc-macro2-eca720657268f2c9/build-script-build\n11.323  rustc            785857 785854   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.324  cc               785856 785703   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustcKNz22k/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.0hbv40a.rc ...\n11.324  sh               785858 785265   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vethf4dd7b0\n11.328  sed              785862 785858   0 \n11.328  cc               785860 785856   0 /usr/bin/cc -m64 /target/debug/build/proc-macro-warning-ad4748846f063e1c/rustcKNz22k/symbols.o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.01ybadcdnvbflbkwushb514lz.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.08jnv9oxll8po4gv427acxkrk.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.0arsd1vmxtl7s1h2wfi0qyy1v.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1e5psbc2xeakdtqtxpefliw4x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.1iwco5l19kdv94powz64i6ioi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.21t60oc3bkp1qxivfw0mv4b9m.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.240bbe5hvht6mplkixhcejwq7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.2pourg03mq1syhqwxjxuecsbg.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.319puy9mkn4vjr0b5nwrp6jkp.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.32dx850a8d3s8zdougkhvpjya.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3g0mv31cl6fjurj24ybge2nr7.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3mcc6dnxq1rq4io9r75esdmle.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3n87luia9op5awyr0cgpctidn.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.3y5kaykbstvv660tx2h14yrxi.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4gnc2arsnxj0lbom7nczbuwsc.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.4y0wlu2qtzpv1xq9zc0nx7w1x.0hbv40a.rc /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c.503ifer2o0yuo5a3o4fjyhlm2.0hbv40a.rc ...\n11.328  ethtool          785861 785858   0 /usr/sbin/ethtool -i vethf4dd7b0\n11.332  collect2         785865 785860   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.334  ld.lld           785867 785865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro-warning-ad4748846f063e1c/build_script_build-ad4748846f063e1c ...\n11.336  systemd-sysctl   785868 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethf4dd7b0 --prefix=/net/ipv4/neigh/vethf4dd7b0 --prefix=/net/ipv6/conf/vethf4dd7b0 --prefix=/net/ipv6/neigh/vethf4dd7b0\n11.336  rust-lld         785867 785865   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc4xYsra.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.336  build-script-bu  785871 785612   0 /target/debug/build/proc-macro-warning-ad4748846f063e1c/build-script-build\n11.342  cc               785873 785702   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcymUPvd/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.343  rustc            785872 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=62b3a44cd46fff0e ...\n11.345  cc               785874 785873   0 /usr/bin/cc -m64 /target/debug/build/quote-5ea12905e6b8e2d7/rustcymUPvd/symbols.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.build_script_build.be9272bffa90a30c-cgu.0.rcgu.o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7.aue2vr7dm1h9os49ysbaxhho1.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.348  collect2         785875 785874   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.349  ld.lld           785876 785875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/quote-5ea12905e6b8e2d7/build_script_build-5ea12905e6b8e2d7 ...\n11.351  rust-lld         785876 785875   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccRlCvHh.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.353  cc               785877 785699   0 /tmp/native-trace-785415-1783996876905/shims/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcO4x7hI/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.355  cc               785894 785877   0 /usr/bin/cc -m64 /target/debug/build/proc-macro2-eca720657268f2c9/rustcO4x7hI/symbols.o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.build_script_build.49139cd1b6dcd00a-cgu.0.r /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9.duehiw2fumovpfv2ox2wgq9zw.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aa ...\n11.357  collect2         785898 785894   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.359  ld.lld           785899 785898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/proc-macro2-eca720657268f2c9/build_script_build-eca720657268f2c9 ...\n11.361  rust-lld         785899 785898   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccTvrvLC.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.404  build-script-bu  785933 785643   0 /target/debug/build/quote-5ea12905e6b8e2d7/build-script-build\n11.407  rustc            785934 785933   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.409  build-script-bu  785936 785643   0 /target/debug/build/proc-macro2-eca720657268f2c9/build-script-build\n11.411  rustc            785937 785936   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version\n11.415  build-script-bu  785939 785643   0 /target/debug/build/proc-macro-warning-ad4748846f063e1c/build-script-build\n11.425  rustc            785943 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"nightly\", \"proc-macro\", \"span-locations\")) -C metadata=f80382781c4ff649 ...\n11.524  rustc            785951 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=13b38aede1a377aa ...\n11.524  rustc            785952 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clone-impls\", \"default\", \"derive\", \"extra-traits\", \"fold\", \"full\", \"parsing\", \"printing\", \"proc-macro\", \"te -C metadata=cc2ee696bc0cfdb9 ...\n11.607  rustc            785970 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.118/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"clone-impls\", \"default\", \"derive\", \"extra-traits\", \"fold\", \"full\", \"parsing\", \"printing\", \"proc-macro\", \"te -C metadata=63304be103d3cbfe ...\n11.607  rustc            785969 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"proc-macro\")) -C metadata=9ab743b18e379101 ...\n11.759  rustc            785991 785612   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_warning --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n11.840  rustc            786003 785643   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro_warning --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"derive_debug\" --check-cfg cfg(docsrs,test) ...\n13.495  systemd-userwor  786175 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n13.496  systemd-userwor  786176 50265    0 /usr/lib/systemd/systemd-userwork xxxxxxxxxxxxxxxx\n13.745  runc             786177 768912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 --log-format json --systemd-cgroup kill --all 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5 9\n13.763  runc             786183 768912   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 --log-format json --systemd-cgroup delete 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5\n13.972  containerd-shim  786190 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9 delete\n13.975  runc             786197 786190   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b --log-format json delete --force 73c6b8f687239001aefe4f9f2c67eb16500660f39bf65dbb32006cecda9a16b5\n14.016  systemd-sysctl   786202 785265   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha0a999b --prefix=/net/ipv4/neigh/vetha0a999b --prefix=/net/ipv6/conf/vetha0a999b --prefix=/net/ipv6/neigh/vetha0a999b\n"
    },
    {
      "argv": [
        "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 783710,
      "build_script_target_dir": "drm-fourcc-13ade45021069b5d",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build",
      "pid": 783710,
      "ppid": 783657,
      "root_cargo_pid": 783657,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "drm-fourcc",
      "cwd": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "event_id": "bsrun:cce3d159f9dd8e33:2e5c452816fbab5c:eb734493b5afb56f",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/drm-fourcc-13ade45021069b5d/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
      "out_dir": "/target/debug/build/drm-fourcc-13ade45021069b5d/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
      "success": true,
      "target": null,
      "version": "2.2.0",
      "_owner": {
        "crate": "drm-fourcc",
        "version": "2.2.0",
        "package_id": "path+file:///tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0#drm-fourcc@2.2.0",
        "manifest_dir": "/tmp/crate-build-ppc64le-0q9az3d8/src/drm-fourcc-2.2.0",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 2910,
    "crate": "drm-fourcc",
    "version": "2.2.0",
    "crate_id": "368523",
    "version_id": "421977",
    "downloads": 3864472,
    "cumulative_downloads": 106536229177,
    "cumulative_share_of_global": 0.39831436638477113,
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
