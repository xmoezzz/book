# `wayland-sys` `0.29.5`

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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
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
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
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
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.10.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-419888-1783994406152193222.map",
  "pid": 419888,
  "ppid": 419821,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-419888-1783994406152193222.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "workspace_root": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "cargo_args": [
    "build",
    "--target",
    "powerpc64le-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
      "name": "pkg-config",
      "version": "0.3.33",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33"
    },
    {
      "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
      "name": "wayland-sys",
      "version": "0.29.5",
      "manifest_path": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5"
    }
  ],
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "exit_code": 0,
  "kind": "exec",
  "pid": 419888,
  "ppid": 419821,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:898cd877e00784f3:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
  "pid": 419888,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:708db8dc04ca5d63:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "0a6b7bab7ad7dbfb4fd91025624d2df45f9a0e16dedcb382fc0e5fdea7d98eb6",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:139772e564b6dffd:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "71f3eee7569220e1ccda82b12df7f358f516b78b3fbbc8116ddbb8bb9521b003",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:38e5c9edf2098036:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "764373e4d5888e607b1164383f1d321079a51d6e99ebaffbdba092832a1e63f9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:d0c59bcac9a3d21e:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "3660dddd3ea907349965b660fb7c79b199848727ea3ccbc6c3fe999ef03d6ffb",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:4b5f756856db138f:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "282e4ca6f1601b9e974daa399bfcbd24c831618dd14e0f8499cf3b567792023c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "used:cc:273a5aff30fa1118:c5cc058098d0afb6:f4f3b06896aae20a",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
  "pid": 419888,
  "sha256": "b6b9a996870318637a165c55e4bab13a3af8f7f9335616da220b89f26cb67839",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
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
  "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "cargo_pkg_name": "wayland-sys",
  "cargo_pkg_version": "0.29.5",
  "context_path": "/tmp/native-trace-419179-1783994403087/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-419179-1783994403087/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 419888,
  "ppid": 419821,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
    "-Wl,--as-needed",
    "-Wl,-Bstatic",
    "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
    "-Wl,-Bdynamic",
    "-lgcc_s",
    "-lutil",
    "-lrt",
    "-lpthread",
    "-lm",
    "-ldl",
    "-lc",
    "-L",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/9",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
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
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
      "kind": "object",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.02.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.01.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.03.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.04.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.05.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.06.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.00.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.07.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.08.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.09.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/deps",
      "kind": "object",
      "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.10.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-419888-1783994406152193222.map",
  "pid": 419888,
  "ppid": 419821,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-419888-1783994406152193222.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
  "parsed_event_count": 1007,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1008,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": "linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.263  cc               424481 424479   0 /usr/bin/cc -m64 /target/debug/build/lock_api-f70595428dab2a94/rustcq1h09q/symbols.o /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94.build_script_build.8402c26e1953cbe2-cgu.0.rcgu /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94.2shqke8567hj3b4ij4v2mgv3o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.267  collect2         424482 424481   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.269  ld.lld           424483 424482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94 ...\n11.272  rust-lld         424483 424482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.322  rustc            424505 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n11.325  build-script-bu  424507 424151   0 /target/debug/build/lock_api-f70595428dab2a94/build-script-build\n11.327  rustc            424508 424507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n11.342  rustc            424514 424507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-c83994f0cd086ac3/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n11.359  rustc            424522 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n11.371  rustc            424527 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"nightly\", \"owning_ref\", \"serde\")) -C metadata=a6d3557504266386 ...\n11.474  rustc            424546 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n11.475  rustc            424547 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=a420f4e3b1a6463a ...\n11.570  runc             424567 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup kill --all 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 9\n11.581  runc             424582 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup delete 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n11.582  rustc            424576 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n11.585  rustc            424581 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n11.590  runc             424589 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup kill --all 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 9\n11.609  runc             424604 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup delete 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n11.801  containerd-shim  424615 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 delete\n11.804  runc             424622 424615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea6 --log-format json delete --force 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n11.819  runc             424627 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2128031445 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n11.821  containerd-shim  424630 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 delete\n11.823  runc             424640 424630   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c138 --log-format json delete --force 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n11.825  exe              424646 424627   0 /proc/self/exe init\n11.830  runc             424656 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup kill --all 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 9\n11.836  sh               424664 424655   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vetha312152\n11.837  ethtool          424665 424664   0 /usr/sbin/ethtool -i vetha312152\n11.837  sed              424666 424664   0 /usr/bin/sed -n s/^driver: //p\n11.842  runc             424669 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup delete 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n11.853  curl             424649 424627   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n11.859  systemd-sysctl   424676 424655   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha312152 --prefix=/net/ipv4/neigh/vetha312152 --prefix=/net/ipv6/conf/vetha312152 --prefix=/net/ipv6/neigh/vetha312152\n11.860  systemd-sysctl   424677 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7edf8f3 --prefix=/net/ipv4/neigh/veth7edf8f3 --prefix=/net/ipv6/conf/veth7edf8f3 --prefix=/net/ipv6/neigh/veth7edf8f3\n11.895  cross            424679 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n11.896  rustc            424682 424679   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.902  rustc            424682 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.914  rustc            424694 424679   0 /home/xmoe/.cargo/bin/rustc -vV\n11.920  rustc            424694 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.929  cargo            424704 424679   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n11.935  cargo            424704 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n11.945  rustc            424713 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.955  rustc            424715 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.967  rustc            424719 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.017  containerd-shim  424724 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 delete\n12.020  runc             424731 424724   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d --log-format json delete --force 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n12.062  systemd-sysctl   424736 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth871c786 --prefix=/net/ipv4/neigh/veth871c786 --prefix=/net/ipv6/conf/veth871c786 --prefix=/net/ipv6/neigh/veth871c786\n12.476  rustc            424762 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client_derive_encode --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prometheus-client-derive-encode-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n12.484  sh               424764 2147557   0 /bin/sh -c which ps\n12.485  which            424764 2147557   0 /usr/bin/which ps\n12.488  sh               424768 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.489  ps               424768 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.513  sh               424771 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.516  cpuUsage.sh      424771 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.517  sed              424772 424771   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.520  cat              424773 424771   0 /usr/bin/cat /proc/2240539/stat\n12.522  cat              424774 424771   0 /usr/bin/cat /proc/4193716/stat\n12.524  sleep            424775 424771   0 /usr/bin/sleep 1\n12.629  cc               424789 424762   0 /tmp/native-trace-423951-1783994413883/shims/cc -Wl,--version-script=/target/debug/deps/rustc2RKFMW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2RKFMW/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustc2RKFMW/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.631  cc               424790 424789   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc2RKFMW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2RKFMW/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustc2RKFMW/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.634  collect2         424791 424790   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc2RKFMW/raw-dylibs ...\n12.636  ld.lld           424792 424791   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc2RKFMW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.637  rust-lld         424792 424791   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n12.711  rustc            424811 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client_derive_encode --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prometheus-client-derive-encode-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n12.736  rustc            424816 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"protobuf\")) ...\n12.846  cc               424825 424811   0 /tmp/native-trace-423863-1783994413829/shims/cc -Wl,--version-script=/target/debug/deps/rustcTeTBVY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTeTBVY/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustcTeTBVY/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.847  cc               424826 424825   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTeTBVY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTeTBVY/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustcTeTBVY/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.850  collect2         424827 424826   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcTeTBVY/raw-dylibs ...\n12.851  ld.lld           424828 424827   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcTeTBVY/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.853  rust-lld         424828 424827   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n12.938  rustc            424846 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"protobuf\")) ...\n13.277  rustc            425032 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.445  rustc            425034 424679   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.450  rustc            425034 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.461  docker           425046 424679   0 /usr/bin/docker --help\n13.473  docker           425057 424679   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.484  runc             425068 1599     0 /usr/bin/runc --version\n13.487  docker-init      425074 1599     0 /usr/bin/docker-init --version\n13.488  docker           425075 424679   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.489  git              425067 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n13.500  runc             425087 1599     0 /usr/bin/runc --version\n13.503  docker-init      425093 1599     0 /usr/bin/docker-init --version\n13.522  rustup           425097 424679   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.526  sed              425106 424771   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.528  rustup           425107 424679   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.528  cat              425108 424771   0 /usr/bin/cat /proc/2240539/stat\n13.530  cat              425110 424771   0 /usr/bin/cat /proc/4193716/stat\n13.551  rustup           425120 424679   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.574  uname            425129 424679   0 /usr/bin/uname -r\n13.590  docker           425130 424679   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.642  systemd-sysctl   425143 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe9cde3 --prefix=/net/ipv4/neigh/vethfe9cde3 --prefix=/net/ipv6/conf/vethfe9cde3 --prefix=/net/ipv6/neigh/vethfe9cde3\n13.642  systemd-sysctl   425144 424655   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaf67a65 --prefix=/net/ipv4/neigh/vethaf67a65 --prefix=/net/ipv6/conf/vethaf67a65 --prefix=/net/ipv6/neigh/vethaf67a65\n13.657  containerd-shim  425174 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b start\n13.661  containerd-shim  425181 425174   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b -address /var/run/docker/containerd/containerd.sock\n13.665  runc             425191 425181   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b\n13.670  exe              425198 425191   0 /proc/self/exe init\n13.707  exe              425207 425191   0 /proc/1599/exe -exec-root=/var/run/docker 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b d7da31e8f8e1\n13.726  exe              425216 1599     0 /proc/self/exe /var/run/docker/netns/9732162b0870 all false\n13.771  runc             425235 425181   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --log-format json --systemd-cgroup start 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b\n13.776  sh               425201 425181   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.777  cargo            425241 425201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.787  cargo-native-tr  425241 425201   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.790  cargo            425242 425241   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.801  rustc            425243 425242   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.812  rustc            425245 425242   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.852  execsnoop        425249 425241   0 /usr/local/bin/execsnoop -t\n13.854  python3          425249 425241   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.533  runc             425252 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1325748569 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.537  exe              425260 425252   0 /proc/self/exe init\n14.551  curl             425262 425252   0 /usr/bin/curl -f http://localhost:9091/healthz\n15.599  cargo            425269 425241   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n15.612  rustc            425270 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.645  rustc            425279 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.648  rustc            425282 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=49e83357d9b1f8a9 ...\n15.648  rustc            425280 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"default\" --cfg ...\n15.648  rustc            425281 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generate\", \"glob\", \"serde\", \"serde_derive\", \"serde_json\", \"tempdir\", \"tera\", \"yaml-rust\")) ...\n15.675  cc               425306 425281   0 /tmp/native-trace-425241-1783994419204/shims/cc -m64 /target/debug/build/woothee-de9e3cc5c3579e7b/rustcaQtTNB/symbols.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.196x3xa.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.677  cc               425307 425306   0 /usr/bin/cc -m64 /target/debug/build/woothee-de9e3cc5c3579e7b/rustcaQtTNB/symbols.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.196x3xa.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.679  collect2         425308 425307   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.681  ld.lld           425309 425308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b ...\n15.682  rust-lld         425309 425308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.718  build-script-bu  425327 425269   0 /target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build\n15.820  cross            425328 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.822  rustc            425331 425328   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.827  rustc            425331 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.839  rustc            425343 425328   0 /home/xmoe/.cargo/bin/rustc -vV\n15.844  rustc            425343 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.853  cargo            425353 425328   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.859  cargo            425353 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.863  rustc            425365 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.870  rustc            425366 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.879  rustc            425372 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.891  rustc            425376 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.952  cross            425381 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.953  rustc            425384 425381   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.958  rustc            425384 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.960  cross            425393 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.961  rustc            425396 425393   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.966  rustc            425396 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.970  rustc            425408 425381   0 /home/xmoe/.cargo/bin/rustc -vV\n15.975  rustc            425408 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.978  rustc            425420 425393   0 /home/xmoe/.cargo/bin/rustc -vV\n15.982  rustc            425420 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.985  cargo            425430 425381   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.991  cargo            425430 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.992  cargo            425440 425393   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.997  cargo            425440 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.002  rustc            425449 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.009  rustc            425451 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.011  rustc            425452 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.018  rustc            425455 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.023  rustc            425458 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.031  rustc            425465 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.842  rustc            425494 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n17.005  rustc            425514 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.024  rustc            425516 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.072  rustc            425518 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.167  rustc            425520 425328   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.172  rustc            425520 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.183  docker           425532 425328   0 /usr/bin/docker --help\n17.188  rustc            425538 425381   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.192  rustc            425551 425393   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.193  rustc            425538 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.196  docker           425560 425328   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.198  rustc            425551 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.205  docker           425574 425381   0 /usr/bin/docker --help\n17.208  runc             425583 1599     0 /usr/bin/runc --version\n17.210  docker           425589 425393   0 /usr/bin/docker --help\n17.212  docker-init      425590 1599     0 /usr/bin/docker-init --version\n17.213  docker           425596 425328   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.219  docker           425611 425381   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.223  docker           425619 425393   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.226  runc             425630 1599     0 /usr/bin/runc --version\n17.229  docker-init      425639 1599     0 /usr/bin/docker-init --version\n17.231  runc             425640 1599     0 /usr/bin/runc --version\n17.234  docker-init      425650 1599     0 /usr/bin/docker-init --version\n17.237  docker           425651 425381   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.237  runc             425652 1599     0 /usr/bin/runc --version\n17.240  docker-init      425663 1599     0 /usr/bin/docker-init --version\n17.242  docker           425666 425393   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.250  runc             425682 1599     0 /usr/bin/runc --version\n17.253  runc             425688 1599     0 /usr/bin/runc --version\n17.254  rustup           425689 425328   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.254  docker-init      425690 1599     0 /usr/bin/docker-init --version\n17.258  docker-init      425704 1599     0 /usr/bin/docker-init --version\n17.260  rustup           425707 425328   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.276  rustup           425716 425381   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.281  rustup           425725 425393   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.283  rustup           425726 425381   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.285  rustup           425735 425328   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.288  rustup           425744 425393   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.307  rustup           425761 425381   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.310  uname            425762 425328   0 /usr/bin/uname -r\n17.311  rustup           425771 425393   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.328  docker           425780 425328   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.333  uname            425786 425381   0 /usr/bin/uname -r\n17.337  uname            425792 425393   0 /usr/bin/uname -r\n17.351  docker           425793 425381   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.361  docker           425805 425393   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.369  systemd-sysctl   425813 425811   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb212ae0 --prefix=/net/ipv4/neigh/vethb212ae0 --prefix=/net/ipv6/conf/vethb212ae0 --prefix=/net/ipv6/neigh/vethb212ae0\n17.371  systemd-sysctl   425818 425812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb31bf6d --prefix=/net/ipv4/neigh/vethb31bf6d --prefix=/net/ipv6/conf/vethb31bf6d --prefix=/net/ipv6/neigh/vethb31bf6d\n17.397  systemd-sysctl   425855 425847   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc0e6e96 --prefix=/net/ipv4/neigh/vethc0e6e96 --prefix=/net/ipv6/conf/vethc0e6e96 --prefix=/net/ipv6/neigh/vethc0e6e96\n17.399  systemd-sysctl   425856 425826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1c34be7 --prefix=/net/ipv4/neigh/veth1c34be7 --prefix=/net/ipv6/conf/veth1c34be7 --prefix=/net/ipv6/neigh/veth1c34be7\n17.405  containerd-shim  425857 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d start\n17.410  containerd-shim  425863 425857   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d -address /var/run/docker/containerd/containerd.sock\n17.413  runc             425875 425863   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d\n17.418  exe              425882 425875   0 /proc/self/exe init\n17.429  systemd-sysctl   425887 425847   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth29845f8 --prefix=/net/ipv4/neigh/veth29845f8 --prefix=/net/ipv6/conf/veth29845f8 --prefix=/net/ipv6/neigh/veth29845f8\n17.429  systemd-sysctl   425888 425826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5271c6e --prefix=/net/ipv4/neigh/veth5271c6e --prefix=/net/ipv6/conf/veth5271c6e --prefix=/net/ipv6/neigh/veth5271c6e\n17.448  exe              425896 425875   0 /proc/1599/exe   \n17.456  containerd-shim  425902 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00 start\n17.460  containerd-shim  425908 425902   0 \n17.463  runc             425919 425908   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00\n17.465  containerd-shim  425920 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 start\n17.469  containerd-shim  425932 425920   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 -address /var/run/docker/containerd/containerd.sock\n17.470  exe              425939 425919   0 /proc/self/exe init\n17.472  exe              425942 1599     0 /proc/self/exe /var/run/docker/netns/7a9b4d175d46 all false\n17.475  runc             425953 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9\n17.481  exe              425963 425953   0 /proc/self/exe init\n17.483  sh               425965 2147557   0 /bin/sh -c which ps\n17.485  which            425965 2147557   0 /usr/bin/which ps\n17.487  sh               425975 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.489  ps               425975 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.503  exe              425987 425919   0 /proc/1599/exe -exec-root=/var/run/docker 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00 d7da31e8f8e1\n17.509  exe              425993 425953   0 /proc/1599/exe -exec-root=/var/run/docker ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 d7da31e8f8e1\n17.516  sh               426000 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.517  cpuUsage.sh      426000 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.520  sed              426001 426000   0 \n17.521  cat              426002 426000   0 /usr/bin/cat /proc/2240539/stat\n17.522  cat              426003 426000   0 /usr/bin/cat /proc/4193716/stat\n17.524  sleep            426006 426000   0 /usr/bin/sleep 1\n17.528  runc             426007 425863   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --log-format json --systemd-cgroup start 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d\n17.531  exe              426014 1599     0 /proc/self/exe /var/run/docker/netns/e53e003403c3 all false\n17.534  sh               425890 425863   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.535  cargo            426021 425890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.537  exe              426022 1599     0 /proc/self/exe /var/run/docker/netns/f7124ee0a3e5 all false\n17.546  cargo-native-tr  426021 425890   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.550  cargo            426035 426021   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.562  rustc            426045 426035   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.572  rustc            426047 426035   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.581  runc             426053 425908   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --log-format json --systemd-cgroup start 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00\n17.586  sh               425968 425908   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.587  cargo            426059 425968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.597  execsnoop        426060 426021   0 /usr/local/bin/execsnoop -t\n17.597  runc             426061 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup start ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9\n17.598  python3          426060 426021   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.600  cargo-native-tr  426059 425968   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.603  sh               425977 425932   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.605  cargo            426070 425977   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.605  cargo            426069 426059   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.615  cargo-native-tr  426070 425977   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.617  rustc            426071 426069   0 \n17.619  cargo            426072 426070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.628  rustc            426074 426069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.630  rustc            426075 426072   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.642  rustc            426080 426072   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.671  execsnoop        426084 426059   0 /usr/local/bin/execsnoop -t\n17.672  python3          426084 426059   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.690  execsnoop        426087 426070   0 /usr/local/bin/execsnoop -t\n17.691  python3          426087 426070   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
}
```

#### Record 15

```json
{
  "argv": [
    "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 420043,
  "build_script_target_dir": "wayland-sys-27676d3a6b3e0c6d",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build",
  "pid": 420043,
  "ppid": 419471,
  "root_cargo_pid": 419471,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "_build_script_manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "_build_script_out_dir": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/out"
}
```

#### Record 16

```json
{
  "crate": "wayland-sys",
  "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "event_id": "bsrun:f714bb6d77536363:0ceb5b341c756bf0:e3ee5c8ba4b678a2",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
  "out_dir": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/out",
  "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
  "success": true,
  "target": null,
  "version": "0.29.5",
  "_owner": {
    "crate": "wayland-sys",
    "version": "0.29.5",
    "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
    "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
    "source": "cwd_prefix"
  }
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T02:00:23.760390+00:00",
  "crate": "wayland-sys",
  "version": "0.29.5",
  "architecture": "ppc64le",
  "duration_seconds": 24.88626892492175,
  "trace_record_count": 16,
  "trace_owner_summary": {
    "owner_package_count": 2,
    "owner_packages": [
      {
        "crate": "pkg-config",
        "version": "0.3.33",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/Cargo.toml"
      },
      {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "manifest_path": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5/Cargo.toml"
      }
    ],
    "attributed_event_count": 13,
    "unattributed_event_count": 3,
    "owners": [
      {
        "crate": "wayland-sys",
        "version": "0.29.5",
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
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "workspace_root": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "cargo_args": [
        "build",
        "--target",
        "powerpc64le-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#pkg-config@0.3.33",
          "name": "pkg-config",
          "version": "0.3.33",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/pkg-config-0.3.33"
        },
        {
          "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
          "name": "wayland-sys",
          "version": "0.29.5",
          "manifest_path": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5"
        }
      ],
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "exit_code": 0,
      "kind": "exec",
      "pid": 419888,
      "ppid": 419821,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:898cd877e00784f3:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
      "pid": 419888,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:708db8dc04ca5d63:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "0a6b7bab7ad7dbfb4fd91025624d2df45f9a0e16dedcb382fc0e5fdea7d98eb6",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:139772e564b6dffd:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "71f3eee7569220e1ccda82b12df7f358f516b78b3fbbc8116ddbb8bb9521b003",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:38e5c9edf2098036:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "764373e4d5888e607b1164383f1d321079a51d6e99ebaffbdba092832a1e63f9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:d0c59bcac9a3d21e:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "3660dddd3ea907349965b660fb7c79b199848727ea3ccbc6c3fe999ef03d6ffb",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:4b5f756856db138f:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "282e4ca6f1601b9e974daa399bfcbd24c831618dd14e0f8499cf3b567792023c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "used:cc:273a5aff30fa1118:c5cc058098d0afb6:f4f3b06896aae20a",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
      "pid": 419888,
      "sha256": "b6b9a996870318637a165c55e4bab13a3af8f7f9335616da220b89f26cb67839",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
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
      "output": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "cargo_pkg_name": "wayland-sys",
      "cargo_pkg_version": "0.29.5",
      "context_path": "/tmp/native-trace-419179-1783994403087/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-419179-1783994403087/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 419888,
      "ppid": 419821,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
        "-Wl,--as-needed",
        "-Wl,-Bstatic",
        "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b22d3a6da.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf6.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6b.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd6004.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec38.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1190dee2e2.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f50bfab.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de53aa.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_alloc-5bc57914b232292d.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a8e6727.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libadler2-1f570ee5c6635aae.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libunwind-545faafa3c69262e.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liblibc-5b1ad6df1855186c.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_core-75c1307561ed9634.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/liballoc-6e6df4ffe0af4d15.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcore-120cbae4e86ec454.rlib",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcompiler_builtins-27cfc16bdf3bb694.rlib",
        "-Wl,-Bdynamic",
        "-lgcc_s",
        "-lutil",
        "-lrt",
        "-lpthread",
        "-lm",
        "-ldl",
        "-lc",
        "-L",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/9",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
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
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/rustcejB05I/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.4b3q5a5fnwn0lxp02pcpu8503.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.5v2fs1hy6kub51t81cbidimho.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8etodlklx88vivl9g7p0k0mah.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8hoqqsxa8rlz8hzfsth6o5d46.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.avruy45lj7ilbqflnej5w3fn1.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d",
          "kind": "object",
          "path": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build_script_build-27676d3a6b3e0c6d.8b1iw3ummwb9fvbe6ykqfskx1.0wnnvxe.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.02.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.01.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.03.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.04.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.05.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.06.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.00.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.07.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.08.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.09.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/deps",
          "kind": "object",
          "path": "/target/debug/deps/libpkg_config-15486b590baf4edc.rlib(pkg_config-15486b590baf4edc.pkg_config.266fe4977005be02-cgu.10.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-419888-1783994406152193222.map",
      "pid": 419888,
      "ppid": 419821,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-419888-1783994406152193222.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
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
      "parsed_event_count": 1007,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1008,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/types.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/types.h:14:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/posix_types.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/stddef.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/uapi/linux/stddef.h:6:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:184:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:46:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/log2.h:12:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/bitops.h:28:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/barrier.h:5:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/alternative.h:9:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/bug.h:108:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/asm-generic/bug.h:22:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/printk.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/linkage.h:8:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/linkage.h:6:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:29:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:12:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:28:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:62:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from /lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/sched.h:13:\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/arch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:61:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\n/lib/modules/6.18.10-100.fc42.x86_64/build/include/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": "linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.263  cc               424481 424479   0 /usr/bin/cc -m64 /target/debug/build/lock_api-f70595428dab2a94/rustcq1h09q/symbols.o /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94.build_script_build.8402c26e1953cbe2-cgu.0.rcgu /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94.2shqke8567hj3b4ij4v2mgv3o.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libautocfg-55afc35e88511a79.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd_detect-e305c7135f5 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libhashbrown-1448c95121de /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_std_workspace_al /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libminiz_oxide-5ad929a15a ...\n11.267  collect2         424482 424481   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n11.269  ld.lld           424483 424482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lock_api-f70595428dab2a94/build_script_build-f70595428dab2a94 ...\n11.272  rust-lld         424483 424482   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/cc70WTEf.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n11.322  rustc            424505 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n11.325  build-script-bu  424507 424151   0 /target/debug/build/lock_api-f70595428dab2a94/build-script-build\n11.327  rustc            424508 424507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --version --verbose\n11.342  rustc            424514 424507   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name probe0 --crate-type=lib --out-dir /target/riscv64gc-unknown-linux-gnu/debug/build/lock_api-c83994f0cd086ac3/out --emit=llvm-ir --target riscv64gc-unknown-linux-gnu -\n11.359  rustc            424522 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n11.371  rustc            424527 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lock_api --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lock_api-0.4.9/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"nightly\", \"owning_ref\", \"serde\")) -C metadata=a6d3557504266386 ...\n11.474  rustc            424546 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.32/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n11.475  rustc            424547 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot_core --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot_core-0.9.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"backtrace\", \"deadlock_detection\", \"nightly\", \"petgraph\", \"thread-id\")) -C metadata=a420f4e3b1a6463a ...\n11.570  runc             424567 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup kill --all 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 9\n11.581  runc             424582 416072   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 --log-format json --systemd-cgroup delete 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n11.582  rustc            424576 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-2.0.28/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n11.585  rustc            424581 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name parking_lot --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/parking_lot-0.12.1/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"arc_lock\", \"deadlock_detection\", \"default\", \"hardware-lock-elision\", \"nightly\", \"owning_ref\", \"send_guard\", ...\n11.590  runc             424589 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup kill --all 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 9\n11.609  runc             424604 416130   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 --log-format json --systemd-cgroup delete 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n11.801  containerd-shim  424615 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9 delete\n11.804  runc             424622 424615   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea6 --log-format json delete --force 443ac554ea3757390e77731ea1dcab149c15f5f809ff8e9d321a2a61be9dea61\n11.819  runc             424627 3919     0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 --log-format json --systemd-cgroup exec --process /tmp/runc-process2128031445 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d2 8af69cb1873a836a060d01c2c8c76e54dfbe8b29caf252604671b1c39d25e6c0\n11.821  containerd-shim  424630 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9 delete\n11.823  runc             424640 424630   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c138 --log-format json delete --force 5d9a290e4d39e1326da003471335591f690fb29d8b77050e897a32ef8c9c1389\n11.825  exe              424646 424627   0 /proc/self/exe init\n11.830  runc             424656 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup kill --all 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 9\n11.836  sh               424664 424655   0 /bin/sh -c /usr/sbin/ethtool -i $1 |/usr/bin/sed -n s/^driver:\\ //p -- vetha312152\n11.837  ethtool          424665 424664   0 /usr/sbin/ethtool -i vetha312152\n11.837  sed              424666 424664   0 /usr/bin/sed -n s/^driver: //p\n11.842  runc             424669 416036   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 --log-format json --systemd-cgroup delete 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n11.853  curl             424649 424627   0 /usr/bin/curl -f http://localhost:9000/minio/health/live\n11.859  systemd-sysctl   424676 424655   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha312152 --prefix=/net/ipv4/neigh/vetha312152 --prefix=/net/ipv6/conf/vetha312152 --prefix=/net/ipv6/neigh/vetha312152\n11.860  systemd-sysctl   424677 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth7edf8f3 --prefix=/net/ipv4/neigh/veth7edf8f3 --prefix=/net/ipv6/conf/veth7edf8f3 --prefix=/net/ipv6/neigh/veth7edf8f3\n11.895  cross            424679 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n11.896  rustc            424682 424679   0 /home/xmoe/.cargo/bin/rustc --print target-list\n11.902  rustc            424682 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n11.914  rustc            424694 424679   0 /home/xmoe/.cargo/bin/rustc -vV\n11.920  rustc            424694 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.929  cargo            424704 424679   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n11.935  cargo            424704 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n11.945  rustc            424713 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n11.955  rustc            424715 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n11.967  rustc            424719 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n12.017  containerd-shim  424724 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5 delete\n12.020  runc             424731 424724   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d --log-format json delete --force 3bbb1877416960fce5e1c9b7cce543bf3d51430be2d6bad1383559121b5341d0\n12.062  systemd-sysctl   424736 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth871c786 --prefix=/net/ipv4/neigh/veth871c786 --prefix=/net/ipv6/conf/veth871c786 --prefix=/net/ipv6/neigh/veth871c786\n12.476  rustc            424762 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client_derive_encode --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prometheus-client-derive-encode-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n12.484  sh               424764 2147557   0 /bin/sh -c which ps\n12.485  which            424764 2147557   0 /usr/bin/which ps\n12.488  sh               424768 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.489  ps               424768 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n12.513  sh               424771 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n12.516  cpuUsage.sh      424771 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n12.517  sed              424772 424771   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n12.520  cat              424773 424771   0 /usr/bin/cat /proc/2240539/stat\n12.522  cat              424774 424771   0 /usr/bin/cat /proc/4193716/stat\n12.524  sleep            424775 424771   0 /usr/bin/sleep 1\n12.629  cc               424789 424762   0 /tmp/native-trace-423951-1783994413883/shims/cc -Wl,--version-script=/target/debug/deps/rustc2RKFMW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2RKFMW/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustc2RKFMW/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.631  cc               424790 424789   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustc2RKFMW/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustc2RKFMW/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustc2RKFMW/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.634  collect2         424791 424790   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc2RKFMW/raw-dylibs ...\n12.636  ld.lld           424792 424791   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o -L/target/debug/deps/rustc2RKFMW/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.637  rust-lld         424792 424791   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/ccGt5Y7M.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/9/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/9/crtbeginS.o ...\n12.711  rustc            424811 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client_derive_encode --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/prometheus-client-derive-encode-0.4.2/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type proc-macro --emit=dep-info,link -C prefer-dynamic -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values()) ...\n12.736  rustc            424816 423971   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"protobuf\")) ...\n12.846  cc               424825 424811   0 /tmp/native-trace-423863-1783994413829/shims/cc -Wl,--version-script=/target/debug/deps/rustcTeTBVY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTeTBVY/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustcTeTBVY/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.847  cc               424826 424825   0 /usr/bin/cc -Wl,--version-script=/target/debug/deps/rustcTeTBVY/list -Wl,--no-undefined-version -m64 /target/debug/deps/rustcTeTBVY/symbols.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.0.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.1.rcgu. /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.prometheus_client_derive_encode.984963a888055e8d-cgu.2.rcgu. /target/debug/deps/rustcTeTBVY/rmeta.o /target/debug/deps/prometheus_client_derive_encode-27350ef26b5b8feb.bzn2y5atv9na0svsarny21x0g.rcgu.o -Wl,--as-needed -Wl,-Bstatic /target/debug/deps/libsyn-7e9d925a67a79fb2.rlib /target/debug/deps/libquote-391e676c4870e7f3.rlib /target/debug/deps/libproc_macro2-ec8ce1d95adbebf3.rlib /target/debug/deps/libunicode_ident-43168511a520ad5f.rlib /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libproc_macro-9a3b801af65 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_literal_escaper- /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 ...\n12.850  collect2         424827 424826   0 /usr/lib/gcc/x86_64-linux-gnu/11/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -fuse-ld=lld -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcTeTBVY/raw-dylibs ...\n12.851  ld.lld           424828 424827   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o -L/target/debug/deps/rustcTeTBVY/raw-dylibs -L/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib ...\n12.853  rust-lld         424828 424827   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/11/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/11/lto-wrapper -plugin-opt=-fresolution=/tmp/ccDiHACO.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -shared -z relro -o /target/debug/deps/libprometheus_client_derive_encode-27350ef26b5b8feb.so /usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/11/crtbeginS.o ...\n12.938  rustc            424846 424151   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name prometheus_client --edition=2021 src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"protobuf\")) ...\n13.277  rustc            425032 424704   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.445  rustc            425034 424679   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n13.450  rustc            425034 424679   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n13.461  docker           425046 424679   0 /usr/bin/docker --help\n13.473  docker           425057 424679   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n13.484  runc             425068 1599     0 /usr/bin/runc --version\n13.487  docker-init      425074 1599     0 /usr/bin/docker-init --version\n13.488  docker           425075 424679   0 /usr/bin/docker info -f {{.SecurityOptions}}\n13.489  git              425067 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n13.500  runc             425087 1599     0 /usr/bin/runc --version\n13.503  docker-init      425093 1599     0 /usr/bin/docker-init --version\n13.522  rustup           425097 424679   0 /home/xmoe/.cargo/bin/rustup toolchain list\n13.526  sed              425106 424771   0 /usr/bin/sed -n s/^cpu\\s//p /proc/stat\n13.528  rustup           425107 424679   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n13.528  cat              425108 424771   0 /usr/bin/cat /proc/2240539/stat\n13.530  cat              425110 424771   0 /usr/bin/cat /proc/4193716/stat\n13.551  rustup           425120 424679   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n13.574  uname            425129 424679   0 /usr/bin/uname -r\n13.590  docker           425130 424679   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n13.642  systemd-sysctl   425143 424675   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethfe9cde3 --prefix=/net/ipv4/neigh/vethfe9cde3 --prefix=/net/ipv6/conf/vethfe9cde3 --prefix=/net/ipv6/neigh/vethfe9cde3\n13.642  systemd-sysctl   425144 424655   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethaf67a65 --prefix=/net/ipv4/neigh/vethaf67a65 --prefix=/net/ipv6/conf/vethaf67a65 --prefix=/net/ipv6/neigh/vethaf67a65\n13.657  containerd-shim  425174 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b start\n13.661  containerd-shim  425181 425174   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b -address /var/run/docker/containerd/containerd.sock\n13.665  runc             425191 425181   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b\n13.670  exe              425198 425191   0 /proc/self/exe init\n13.707  exe              425207 425191   0 /proc/1599/exe -exec-root=/var/run/docker 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b d7da31e8f8e1\n13.726  exe              425216 1599     0 /proc/self/exe /var/run/docker/netns/9732162b0870 all false\n13.771  runc             425235 425181   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936 --log-format json --systemd-cgroup start 0ab57208798e9a679f69bce552ae2ff342c582f088850baa822676c8936be84b\n13.776  sh               425201 425181   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n13.777  cargo            425241 425201   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n13.787  cargo-native-tr  425241 425201   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n13.790  cargo            425242 425241   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n13.801  rustc            425243 425242   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n13.812  rustc            425245 425242   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n13.852  execsnoop        425249 425241   0 /usr/local/bin/execsnoop -t\n13.854  python3          425249 425241   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n14.533  runc             425252 4003366   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 --log-format json --systemd-cgroup exec --process /tmp/runc-process1325748569 --detach --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197 d4fd13834bd9b67b200ef9d2bf3916f57dab4b392de3619fe5f9769d197daa49\n14.537  exe              425260 425252   0 /proc/self/exe init\n14.551  curl             425262 425252   0 /usr/bin/curl -f http://localhost:9091/healthz\n15.599  cargo            425269 425241   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo build --target aarch64-unknown-linux-gnu\n15.612  rustc            425270 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.645  rustc            425279 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name memchr --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/memchr-2.8.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"alloc\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.648  rustc            425282 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name lazy_static --edition=2015 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/lazy_static-1.5.0/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"spin\", \"spin_no_std\")) -C metadata=49e83357d9b1f8a9 ...\n15.648  rustc            425280 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_syntax --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-syntax-0.8.11/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"default\" --cfg ...\n15.648  rustc            425281 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"default\", \"generate\", \"glob\", \"serde\", \"serde_derive\", \"serde_json\", \"tempdir\", \"tera\", \"yaml-rust\")) ...\n15.675  cc               425306 425281   0 /tmp/native-trace-425241-1783994419204/shims/cc -m64 /target/debug/build/woothee-de9e3cc5c3579e7b/rustcaQtTNB/symbols.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.196x3xa.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.677  cc               425307 425306   0 /usr/bin/cc -m64 /target/debug/build/woothee-de9e3cc5c3579e7b/rustcaQtTNB/symbols.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.2k4jd0kc66a0l8m8ba7h41yuz.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.5l3vdkenm3b5xk25jxp6agz6b.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.6qhxdgj0amkfxtldu61a3p9k0.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.akkayj75v0zd2tbu9ppbpdis1.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.btcrhonhm3bmndhx1jrq0i6n6.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.dm1epqzmf52m569dt3yap89c7.196x3xa.rcgu.o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b.cck153eslx60di55i2stdjxad.196x3xa.rcgu.o -Wl,--as-needed -Wl,-Bstatic /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libstd-d1237ef7159db0a2.r /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libpanic_unwind-4be5972b2 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libobject-2a81194c9d07bbf /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libmemchr-ea71fa85f6699d6 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libaddr2line-a79a8816d9fd /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libgimli-46dc78dc6a8cb06a /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/libcfg_if-0ce073fff809ec3 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib/librustc_demangle-146c3f1 ...\n15.679  collect2         425308 425307   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n15.681  ld.lld           425309 425308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/woothee-de9e3cc5c3579e7b/build_script_build-de9e3cc5c3579e7b ...\n15.682  rust-lld         425309 425308   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cclCQlFT.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n15.718  build-script-bu  425327 425269   0 /target/debug/build/woothee-de9e3cc5c3579e7b/build-script-build\n15.820  cross            425328 4193716   0 /home/xmoe/.cargo/bin/cross build --target aarch64-unknown-linux-gnu\n15.822  rustc            425331 425328   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.827  rustc            425331 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.839  rustc            425343 425328   0 /home/xmoe/.cargo/bin/rustc -vV\n15.844  rustc            425343 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.853  cargo            425353 425328   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.859  cargo            425353 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform aarch64-unknown-linux-gnu\n15.863  rustc            425365 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name aho_corasick --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/aho-corasick-1.1.4/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"perf-literal\" --cfg feature=\"std\" --check-cfg cfg(docsrs,test) ...\n15.870  rustc            425366 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.879  rustc            425372 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n15.891  rustc            425376 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target aarch64-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n15.952  cross            425381 4193716   0 /home/xmoe/.cargo/bin/cross build --target riscv64gc-unknown-linux-gnu\n15.953  rustc            425384 425381   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.958  rustc            425384 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.960  cross            425393 4193716   0 /home/xmoe/.cargo/bin/cross build --target powerpc64le-unknown-linux-gnu\n15.961  rustc            425396 425393   0 /home/xmoe/.cargo/bin/rustc --print target-list\n15.966  rustc            425396 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print target-list\n15.970  rustc            425408 425381   0 /home/xmoe/.cargo/bin/rustc -vV\n15.975  rustc            425408 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.978  rustc            425420 425393   0 /home/xmoe/.cargo/bin/rustc -vV\n15.982  rustc            425420 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n15.985  cargo            425430 425381   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.991  cargo            425430 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform riscv64gc-unknown-linux-gnu\n15.992  cargo            425440 425393   0 /home/xmoe/.cargo/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n15.997  cargo            425440 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1 --filter-platform powerpc64le-unknown-linux-gnu\n16.002  rustc            425449 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.009  rustc            425451 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.011  rustc            425452 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.018  rustc            425455 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.023  rustc            425458 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target riscv64gc-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.031  rustc            425465 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --target powerpc64le-unknown-linux-gnu --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot ...\n16.842  rustc            425494 425269   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name regex_automata --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/regex-automata-0.4.15/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --allow=unexpected_cfgs --check-cfg cfg(docsrs_regex) --cfg feature=\"alloc\" --cfg ...\n17.005  rustc            425514 425353   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.024  rustc            425516 425430   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.072  rustc            425518 425440   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.167  rustc            425520 425328   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.172  rustc            425520 425328   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.183  docker           425532 425328   0 /usr/bin/docker --help\n17.188  rustc            425538 425381   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.192  rustc            425551 425393   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n17.193  rustc            425538 425381   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.196  docker           425560 425328   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.198  rustc            425551 425393   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n17.205  docker           425574 425381   0 /usr/bin/docker --help\n17.208  runc             425583 1599     0 /usr/bin/runc --version\n17.210  docker           425589 425393   0 /usr/bin/docker --help\n17.212  docker-init      425590 1599     0 /usr/bin/docker-init --version\n17.213  docker           425596 425328   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.219  docker           425611 425381   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.223  docker           425619 425393   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n17.226  runc             425630 1599     0 /usr/bin/runc --version\n17.229  docker-init      425639 1599     0 /usr/bin/docker-init --version\n17.231  runc             425640 1599     0 /usr/bin/runc --version\n17.234  docker-init      425650 1599     0 /usr/bin/docker-init --version\n17.237  docker           425651 425381   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.237  runc             425652 1599     0 /usr/bin/runc --version\n17.240  docker-init      425663 1599     0 /usr/bin/docker-init --version\n17.242  docker           425666 425393   0 /usr/bin/docker info -f {{.SecurityOptions}}\n17.250  runc             425682 1599     0 /usr/bin/runc --version\n17.253  runc             425688 1599     0 /usr/bin/runc --version\n17.254  rustup           425689 425328   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.254  docker-init      425690 1599     0 /usr/bin/docker-init --version\n17.258  docker-init      425704 1599     0 /usr/bin/docker-init --version\n17.260  rustup           425707 425328   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.276  rustup           425716 425381   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.281  rustup           425725 425393   0 /home/xmoe/.cargo/bin/rustup toolchain list\n17.283  rustup           425726 425381   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.285  rustup           425735 425328   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.288  rustup           425744 425393   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n17.307  rustup           425761 425381   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.310  uname            425762 425328   0 /usr/bin/uname -r\n17.311  rustup           425771 425393   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n17.328  docker           425780 425328   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.333  uname            425786 425381   0 /usr/bin/uname -r\n17.337  uname            425792 425393   0 /usr/bin/uname -r\n17.351  docker           425793 425381   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.361  docker           425805 425393   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n17.369  systemd-sysctl   425813 425811   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb212ae0 --prefix=/net/ipv4/neigh/vethb212ae0 --prefix=/net/ipv6/conf/vethb212ae0 --prefix=/net/ipv6/neigh/vethb212ae0\n17.371  systemd-sysctl   425818 425812   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethb31bf6d --prefix=/net/ipv4/neigh/vethb31bf6d --prefix=/net/ipv6/conf/vethb31bf6d --prefix=/net/ipv6/neigh/vethb31bf6d\n17.397  systemd-sysctl   425855 425847   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethc0e6e96 --prefix=/net/ipv4/neigh/vethc0e6e96 --prefix=/net/ipv6/conf/vethc0e6e96 --prefix=/net/ipv6/neigh/vethc0e6e96\n17.399  systemd-sysctl   425856 425826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth1c34be7 --prefix=/net/ipv4/neigh/veth1c34be7 --prefix=/net/ipv6/conf/veth1c34be7 --prefix=/net/ipv6/neigh/veth1c34be7\n17.405  containerd-shim  425857 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d start\n17.410  containerd-shim  425863 425857   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d -address /var/run/docker/containerd/containerd.sock\n17.413  runc             425875 425863   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d\n17.418  exe              425882 425875   0 /proc/self/exe init\n17.429  systemd-sysctl   425887 425847   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth29845f8 --prefix=/net/ipv4/neigh/veth29845f8 --prefix=/net/ipv6/conf/veth29845f8 --prefix=/net/ipv6/neigh/veth29845f8\n17.429  systemd-sysctl   425888 425826   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth5271c6e --prefix=/net/ipv4/neigh/veth5271c6e --prefix=/net/ipv6/conf/veth5271c6e --prefix=/net/ipv6/neigh/veth5271c6e\n17.448  exe              425896 425875   0 /proc/1599/exe   \n17.456  containerd-shim  425902 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00 start\n17.460  containerd-shim  425908 425902   0 \n17.463  runc             425919 425908   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00\n17.465  containerd-shim  425920 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 start\n17.469  containerd-shim  425932 425920   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 -address /var/run/docker/containerd/containerd.sock\n17.470  exe              425939 425919   0 /proc/self/exe init\n17.472  exe              425942 1599     0 /proc/self/exe /var/run/docker/netns/7a9b4d175d46 all false\n17.475  runc             425953 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9\n17.481  exe              425963 425953   0 /proc/self/exe init\n17.483  sh               425965 2147557   0 /bin/sh -c which ps\n17.485  which            425965 2147557   0 /usr/bin/which ps\n17.487  sh               425975 2147557   0 /bin/sh -c /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.489  ps               425975 2147557   0 /usr/bin/ps -ax -o pid=,ppid=,pcpu=,pmem=,command=\n17.503  exe              425987 425919   0 /proc/1599/exe -exec-root=/var/run/docker 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00 d7da31e8f8e1\n17.509  exe              425993 425953   0 /proc/1599/exe -exec-root=/var/run/docker ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9 d7da31e8f8e1\n17.516  sh               426000 2147557   0 /bin/sh -c \"/home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh\" 2240\n17.517  cpuUsage.sh      426000 2147557   0 /home/xmoe/.vscode-server/cli/servers/Stable-fc3def6774c76082adf699d366f31a557ce5573f/server/out/vs/base/node/cpuUsage.sh 2240539 4193716\n17.520  sed              426001 426000   0 \n17.521  cat              426002 426000   0 /usr/bin/cat /proc/2240539/stat\n17.522  cat              426003 426000   0 /usr/bin/cat /proc/4193716/stat\n17.524  sleep            426006 426000   0 /usr/bin/sleep 1\n17.528  runc             426007 425863   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d --log-format json --systemd-cgroup start 70986ffb1bd22a4cfb38f0694a47e03d3254da15e14c6bb590e6116053d4595d\n17.531  exe              426014 1599     0 /proc/self/exe /var/run/docker/netns/e53e003403c3 all false\n17.534  sh               425890 425863   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.535  cargo            426021 425890   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n17.537  exe              426022 1599     0 /proc/self/exe /var/run/docker/netns/f7124ee0a3e5 all false\n17.546  cargo-native-tr  426021 425890   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n17.550  cargo            426035 426021   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.562  rustc            426045 426035   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.572  rustc            426047 426035   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.581  runc             426053 425908   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324 --log-format json --systemd-cgroup start 59bf0a7d5ecd049a55a54a3d8e65a11aa5d96e5aa4f1658c9280c6e4324a9b00\n17.586  sh               425968 425908   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.587  cargo            426059 425968   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.597  execsnoop        426060 426021   0 /usr/local/bin/execsnoop -t\n17.597  runc             426061 425932   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6 --log-format json --systemd-cgroup start ff0742b4eefe303e4b2ccb919b07a412ad33414bae40b65792f78faf0e6dc7b9\n17.598  python3          426060 426021   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.600  cargo-native-tr  426059 425968   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n17.603  sh               425977 425932   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n17.605  cargo            426070 425977   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.605  cargo            426069 426059   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.615  cargo-native-tr  426070 425977   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n17.617  rustc            426071 426069   0 \n17.619  cargo            426072 426070   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n17.628  rustc            426074 426069   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.630  rustc            426075 426072   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n17.642  rustc            426080 426072   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n17.671  execsnoop        426084 426059   0 /usr/local/bin/execsnoop -t\n17.672  python3          426084 426059   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.690  execsnoop        426087 426070   0 /usr/local/bin/execsnoop -t\n17.691  python3          426087 426070   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n"
    },
    {
      "argv": [
        "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 420043,
      "build_script_target_dir": "wayland-sys-27676d3a6b3e0c6d",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build",
      "pid": 420043,
      "ppid": 419471,
      "root_cargo_pid": 419471,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "wayland-sys",
      "cwd": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "event_id": "bsrun:f714bb6d77536363:0ceb5b341c756bf0:e3ee5c8ba4b678a2",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
      "out_dir": "/target/debug/build/wayland-sys-27676d3a6b3e0c6d/out",
      "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
      "success": true,
      "target": null,
      "version": "0.29.5",
      "_owner": {
        "crate": "wayland-sys",
        "version": "0.29.5",
        "package_id": "path+file:///tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5#wayland-sys@0.29.5",
        "manifest_dir": "/tmp/crate-build-ppc64le-7zipb5uk/src/wayland-sys-0.29.5",
        "source": "cwd_prefix"
      }
    }
  ],
  "rustc_trace_records": [],
  "item": {
    "rank": 1791,
    "crate": "wayland-sys",
    "version": "0.29.5",
    "crate_id": "3150",
    "version_id": "608613",
    "downloads": 8680429,
    "cumulative_downloads": 100090352743,
    "cumulative_share_of_global": 0.3742147224661038,
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
