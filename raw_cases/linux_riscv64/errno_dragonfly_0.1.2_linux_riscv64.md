# `errno-dragonfly` `0.1.2`

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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
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
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395",
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
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-137022-1783993044724710478.map",
  "pid": 137022,
  "ppid": 136999,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-137022-1783993044724710478.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cargo_manifest_dir"
  }
}
```

## Root-owned native flows

## Flow 001

Artifact: `/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a`

Owner: `errno-dragonfly` `0.1.2`

### Source files

* `/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/src/errno.c`

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
    "-Wall",
    "-Wextra",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
    "-c",
    "src/errno.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 137049,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/errno.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/",
    "-dumpbase",
    "ea708c7824d36062-errno.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "src": "src/errno.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 137050,
  "ppid": 137049,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "root_cargo_pid": 136274,
  "build_script_root_pid": 137043,
  "build_script_related": true,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 137054,
  "ppid": 137043,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "root_cargo_pid": 136274,
  "build_script_root_pid": 137043,
  "build_script_related": true,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
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
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "cargo_args": [
    "build",
    "--target",
    "riscv64gc-unknown-linux-gnu"
  ],
  "workspace_default_members": [
    "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2"
  ],
  "packages": [
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
      "name": "cc",
      "version": "1.2.67",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
    },
    {
      "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
      "name": "errno-dragonfly",
      "version": "0.1.2",
      "manifest_path": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/Cargo.toml",
      "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
      "name": "find-msvc-tools",
      "version": "0.1.9",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "name": "libc",
      "version": "0.2.186",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
    },
    {
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
      "name": "shlex",
      "version": "2.0.1",
      "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
    }
  ],
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "kind": "exec",
  "pid": 136428,
  "ppid": 136329,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:8bcf3eff2fa52fa3:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
  "pid": 136428,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:2a6962d9700b3a6f:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
  "pid": 136428,
  "sha256": "64eb7fc5099e1948e306f9c8a523b826941e7f6f829933101392444b06b4538e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:f90a82b8b08a57e8:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
  "pid": 136428,
  "sha256": "e5617ac33c84f22a8b2a806d2362095876748795e0fc941671566e69acc805b4",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:0ce2bb3a4c72bd09:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
  "pid": 136428,
  "sha256": "1fd12f1851556a6df4ee5c71d6fe92d121e5a11cebbbfa97cc71ba46b14b7692",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:2039e6bbdc279ca3:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
  "pid": 136428,
  "sha256": "d112027f03bd03220f5b546fa33b20cb5c6eed11120d0c291cc6bd2ddb069f48",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "consumer_kind": "linker",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "used:cc:f7a275179e4f3c0d:8c799a9b888348bf:1d8ed5dafb3ff8ae",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
  "pid": 136428,
  "sha256": "c668b521a73e76c017ee2e7b87ff814174e0875a9f9435ddba2cfb922d96224a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
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
  "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "cargo_pkg_name": "libc",
  "cargo_pkg_version": "0.2.186",
  "context_path": "/tmp/native-trace-135773-1783993040646/events/00000000-root-context.jsonl",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-135773-1783993040646/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 136428,
  "ppid": 136329,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN",
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
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
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
      "kind": "object",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-136428-1783993043507949365.map",
  "pid": 136428,
  "ppid": 136329,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-136428-1783993043507949365.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "exit_code": 0,
  "kind": "exec",
  "pid": 137022,
  "ppid": 136999,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:a3eee9239f84efe8:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
  "pid": 137022,
  "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:c1ed862cfff17b95:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "65e02699a94199f2c9ed5d6158e35de9100f8753d2fd0bba971c5b0895b605c9",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:e19c0dbd7ca62cf6:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "125f0a189ff3efd09e679b70519393d390b94ee4afe664fbe5974b484b95bb4f",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:fa2fc1ad4a9984bf:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "0c2384bc5e11cc2d2fdf72c0e7ad95e9ba1241acbaabe5c8b33e1c67a8e7da0a",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:1169987e729c8448:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "a2323576c6a9583ad720f21ed2a56bfc76534c2eb55b36ad31da5d9895cd5e85",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:2464d7a65ccdf87f:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "459fe9487d3e51d8e2bfd5ca6161e8027c7e2a3b23d207ec3a5b897e9fe7fa4c",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:af709c13fa82b83e:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "edcdb51dee83aeb25a2812ed65bb57727b09a4331569aa6d0d354bab69d5d66e",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:6f6e8110127f9770:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "73b025275731d5cd76e415e614f692ad7ac56412c666518242c84996dd80d718",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:afb66abb860c3d3a:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "bdf4fd06abe8b1d5a343d9c3fc93b4eb4954dd5c6269eb0831d66a543c40ca58",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "consumer_kind": "linker",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "used:cc:46febdad91dc0cb4:df35bd192616d580:ba5e1f9bac558b7d",
  "exit_code": 0,
  "input_kind": "object",
  "kind": "used_input",
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
  "pid": 137022,
  "sha256": "d3c9e177b473c32b15bc199e76757f875156b8baf830111ebdd5dd71e46ea7a7",
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "exit_code": 0,
  "inputs": [
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o"
  ],
  "kind": "link",
  "lib_paths": [
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
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
  "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
  "shared": false,
  "static_link": false,
  "success": true,
  "tool": "cc",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cargo_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "cargo_pkg_name": "errno-dragonfly",
  "cargo_pkg_version": "0.1.2",
  "context_path": "/tmp/native-trace-135773-1783993040646/events/00000000-root-context.jsonl",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "exit_code": 0,
  "host": null,
  "kind": "exec_context",
  "metadata_path": "/tmp/native-trace-135773-1783993040646/events/00000000-cargo-metadata.json",
  "num_jobs": null,
  "opt_level": null,
  "out_dir": null,
  "pid": 137022,
  "ppid": 136999,
  "profile": null,
  "real_tool": "/usr/bin/cc",
  "root_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "success": true,
  "target": null,
  "tool": "cc",
  "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
    "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
    "-fuse-ld=lld",
    "-Wl,--eh-frame-hdr",
    "-Wl,-z,noexecstack",
    "-L",
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
    "-o",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
    "-Wl,--gc-sections",
    "-pie",
    "-Wl,-z,relro,-z,now",
    "-nodefaultlibs"
  ],
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "directories": [
    "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
    "/usr/lib/gcc/x86_64-linux-gnu/11",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
    "/target/debug/build/errno-dragonfly-230bb91007c5e395",
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
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
      "source": "link_trace"
    },
    {
      "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
      "kind": "object",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
  "map_path": "/tmp/native-trace-link-cc-137022-1783993044724710478.map",
  "pid": 137022,
  "ppid": 136999,
  "real_tool": "/usr/bin/cc",
  "success": true,
  "tool": "cc",
  "trace_args": [
    "-Wl,--trace",
    "-Wl,-Map,/tmp/native-trace-link-cc-137022-1783993044724710478.map"
  ],
  "trace_mode": "driver",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
  "parse_error_count": 2,
  "parsed_event_count": 1197,
  "phase": "stop",
  "platform": "linux_ebpf",
  "raw_event_count": 1199,
  "spawn_error": null,
  "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
  "stdout": " rustc            141880 141497   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.252  docker           141897 141331   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.254  rustc            141878 141609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.266  rustc            141880 141497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.271  docker           141916 141609   0 /usr/bin/docker --help\n16.284  build-script-bu  141926 141141   0 /target/debug/build/ahash-513e4052a7199891/build-script-build\n16.294  rustc            141935 141926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n16.297  docker           141936 141497   0 /usr/bin/docker --help\n16.307  rustc            141940 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.308  docker           141941 141609   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.331  runc             141967 1599     0 /usr/bin/runc --version\n16.336  docker           141971 141497   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.339  docker-init      141977 1599     0 /usr/bin/docker-init --version\n16.342  docker           141981 141609   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.347  systemd-sysctl   141987 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth462e707 --prefix=/net/ipv4/neigh/veth462e707 --prefix=/net/ipv6/conf/veth462e707 --prefix=/net/ipv6/neigh/veth462e707\n16.350  systemd-sysctl   141988 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth169aacc --prefix=/net/ipv4/neigh/veth169aacc --prefix=/net/ipv6/conf/veth169aacc --prefix=/net/ipv6/neigh/veth169aacc\n16.362  runc             141995 1599     0 /usr/bin/runc --version\n16.368  docker-init      142001 1599     0 /usr/bin/docker-init --version\n16.369  runc             142002 1599     0 \n16.380  docker-init      142008 1599     0 /usr/bin/docker-init --version\n16.384  docker           142009 141497   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.391  containerd-shim  142015 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c start\n16.397  rustc            142019 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.401  containerd-shim  142030 142015   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c -address /var/run/docker/containerd/containerd.sock\n16.401  rustup           142031 141609   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.403  rustc            142026 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.404  runc             142040 142030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c\n16.409  runc             142054 1599     0 /usr/bin/runc --version\n16.413  rustup           142063 141609   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.413  exe              142066 142040   0 /proc/self/exe init\n16.416  docker-init      142068 1599     0 /usr/bin/docker-init --version\n16.440  rustc            142083 140648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"static\")) -C metadata=90b92fb64bbd87d9 ...\n16.450  rustup           142093 141609   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.450  rustup           142092 141497   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.461  rustup           142114 141497   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.474  exe              142125 142040   0 /proc/1599/exe -exec-root=/var/run/docker 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c d7da31e8f8e1\n16.496  uname            142134 141609   0 /usr/bin/uname -r\n16.499  rustup           142135 141497   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.514  exe              142146 1599     0 /proc/self/exe /var/run/docker/netns/005e12871cc2 all false\n16.526  docker           142152 141609   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.537  uname            142160 141497   0 /usr/bin/uname -r\n16.564  rustc            142171 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.572  docker           142176 141497   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.591  runc             142205 142030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --log-format json --systemd-cgroup start 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c\n16.600  systemd-sysctl   142215 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6a03aef --prefix=/net/ipv4/neigh/veth6a03aef --prefix=/net/ipv6/conf/veth6a03aef --prefix=/net/ipv6/neigh/veth6a03aef\n16.602  sh               142085 142030   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.602  systemd-sysctl   142217 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha3ef1ab --prefix=/net/ipv4/neigh/vetha3ef1ab --prefix=/net/ipv6/conf/vetha3ef1ab --prefix=/net/ipv6/neigh/vetha3ef1ab\n16.603  cargo            142220 142085   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.624  cargo-native-tr  142220 142085   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.629  cargo            142238 142220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.648  containerd-shim  142257 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 start\n16.651  rustc            142259 142238   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.653  containerd-shim  142268 142257   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 -address /var/run/docker/containerd/containerd.sock\n16.658  runc             142277 142268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619\n16.664  cc               142283 142083   0 /tmp/native-trace-140328-1783993055854/shims/cc -m64 /target/debug/build/lzma-sys-5c2d69c993aabfec/rustce2Yd57/symbols.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.0emzgrjz0mbyz0ub8m5kx31rw.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.187gf3rk9m02q37c41q8g47of.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1iol46f9eey230dngrt6dfk7a.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1vig8wx5w91kvz3m9coj07849.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1z4p4hm1b81ngojvpej1tkj3b.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2bx6tmmw6rbv54jkfxabmqaqr.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ds6mcm4sy54wpwon2pfzz7em.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ecl7lbofydiczussh3a6t99m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2gcdf4joxpngceva48u1itnne.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.30x6duc672p5ev99dq8q3ox85.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.31tf5rfl0pi4nq6aipe6f7f70.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.33pc1db836fpagekeyle2f84m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.34gye9xshswyamigntl2p748y.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3b7x7fj1g5vox39qkt0u0x1lz.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3h9ckas9gbm05a2u3v7xt2r96.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3nhkxpupblrm2ni7qc1iu05v7.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.492iydcghkt8blkq5e79csf9l.1it1kcv.rcgu.o ...\n16.666  exe              142290 142277   0 /proc/self/exe init\n16.667  cc               142291 142283   0 /usr/bin/cc -m64 /target/debug/build/lzma-sys-5c2d69c993aabfec/rustce2Yd57/symbols.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.0emzgrjz0mbyz0ub8m5kx31rw.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.187gf3rk9m02q37c41q8g47of.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1iol46f9eey230dngrt6dfk7a.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1vig8wx5w91kvz3m9coj07849.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1z4p4hm1b81ngojvpej1tkj3b.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2bx6tmmw6rbv54jkfxabmqaqr.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ds6mcm4sy54wpwon2pfzz7em.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ecl7lbofydiczussh3a6t99m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2gcdf4joxpngceva48u1itnne.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.30x6duc672p5ev99dq8q3ox85.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.31tf5rfl0pi4nq6aipe6f7f70.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.33pc1db836fpagekeyle2f84m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.34gye9xshswyamigntl2p748y.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3b7x7fj1g5vox39qkt0u0x1lz.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3h9ckas9gbm05a2u3v7xt2r96.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3nhkxpupblrm2ni7qc1iu05v7.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.492iydcghkt8blkq5e79csf9l.1it1kcv.rcgu.o ...\n16.675  rustc            142287 142238   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.675  collect2         142295 142291   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.675  systemd-sysctl   142294 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth15404de --prefix=/net/ipv4/neigh/veth15404de --prefix=/net/ipv6/conf/veth15404de --prefix=/net/ipv6/neigh/veth15404de\n16.675  systemd-sysctl   142293 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethede48fb --prefix=/net/ipv4/neigh/vethede48fb --prefix=/net/ipv6/conf/vethede48fb --prefix=/net/ipv6/neigh/vethede48fb\n16.680  ld.lld           142296 142295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec ...\n16.680  rust-lld         142296 142295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.695  containerd-shim  142301 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa start\n16.700  execsnoop        142321 142220   0 /usr/local/bin/execsnoop -t\n16.701  python3          142321 142220   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.703  containerd-shim  142326 142301   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa -address /var/run/docker/containerd/containerd.sock\n16.713  runc             142341 142326   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa\n16.713  rustc            142331 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.727  exe              142349 142341   0 /proc/self/exe init\n16.759  exe              142370 142277   0 /proc/1599/exe -exec-root=/var/run/docker 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 d7da31e8f8e1\n16.768  exe              142376 142341   0 /proc/1599/exe -exec-root=/var/run/docker 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa d7da31e8f8e1\n16.797  rustc            142387 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=35aaec97f13a8ad6 ...\n16.804  exe              142392 1599     0 /proc/self/exe /var/run/docker/netns/fd6470ee62b8 all false\n16.812  exe              142403 1599     0 /proc/self/exe /var/run/docker/netns/701b52d0100d all false\n16.818  git              142393 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n16.859  build-script-bu  142420 140648   0 /target/debug/build/lzma-sys-5c2d69c993aabfec/build-script-build\n16.862  pkg-config       142421 142420   0 /tmp/native-trace-140328-1783993055854/shims/pkg-config --libs --cflags liblzma\n16.864  pkg-config       142422 142421   0 /usr/bin/pkg-config --libs --cflags liblzma\n16.872  aarch64-linux-g  142423 142420   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/lzma-sys-3402062eb38469a1/out/15694474413922396716detect_compiler_family.c\n16.875  cc1              142424 142423   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/lzma-sys-3402062eb38469a1/out/15694474413922396716detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.883  runc             142429 142268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --log-format json --systemd-cgroup start 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619\n16.883  aarch64-linux-g  142430 142420   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.888  rustc            142431 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.893  aarch64-linux-g  142432 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n16.896  cc1              142442 142432   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n16.900  sh               142352 142268   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.903  cargo            142446 142352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.903  rustc            142441 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=bdd4007228ca136e ...\n16.911  runc             142452 142326   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --log-format json --systemd-cgroup start 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa\n16.916  rustc            142451 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=917cf36d7c182416 ...\n16.921  cargo-native-tr  142446 142352   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.921  sh               142362 142326   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.922  cargo            142463 142362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.925  cargo            142465 142446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.937  cargo-native-tr  142463 142362   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.943  as               142470 142432   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n16.944  cargo            142472 142463   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.947  rustc            142471 142465   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.958  rustc            142474 142472   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.962  aarch64-linux-g  142476 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n16.962  rustc            142475 142465   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.964  cc1              142477 142476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n16.979  rustc            142482 142472   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.985  as               142483 142476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n16.989  execsnoop        142485 142446   0 /usr/local/bin/execsnoop -t\n16.990  python3          142485 142446   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.001  aarch64-linux-g  142490 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.003  cc1              142491 142490   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.004  execsnoop        142492 142463   0 /usr/local/bin/execsnoop -t\n17.006  python3          142492 142463   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.014  rustc            142498 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=85aba2bb86f02949 ...\n17.042  rustc            142506 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.063  as               142511 142490   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.076  aarch64-linux-g  142512 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.078  cc1              142513 142512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.100  rustc            142517 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=ada5e235c1649296 ...\n17.111  as               142519 142512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.121  rustc            142526 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.129  aarch64-linux-g  142528 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.132  cc1              142529 142528   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.170  rustc            142536 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=bd1c4082384a6a98 ...\n17.175  as               142538 142528   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.189  aarch64-linux-g  142542 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.192  cc1              142543 142542   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.235  as               142544 142542   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.251  aarch64-linux-g  142545 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.254  cc1              142546 142545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.265  rustc            142550 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.293  as               142555 142545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.310  aarch64-linux-g  142556 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.313  cc1              142557 142556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.422  as               142558 142556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.446  aarch64-linux-g  142559 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.449  cc1              142560 142559   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.501  as               142564 142559   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.515  aarch64-linux-g  142567 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.517  cc1              142569 142567   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.549  as               142570 142567   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.562  aarch64-linux-g  142571 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.564  cc1              142572 142571   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.597  as               142576 142571   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.611  aarch64-linux-g  142577 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.613  cc1              142578 142577   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.640  as               142579 142577   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.653  aarch64-linux-g  142580 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.655  cc1              142581 142580   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.691  as               142582 142580   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.706  aarch64-linux-g  142583 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.708  cc1              142584 142583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.742  as               142585 142583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.756  aarch64-linux-g  142586 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.758  cc1              142587 142586   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.791  as               142588 142586   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.804  aarch64-linux-g  142589 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.806  cc1              142590 142589   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.837  as               142591 142589   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.850  aarch64-linux-g  142592 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.852  cc1              142593 142592   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.882  as               142594 142592   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.894  aarch64-linux-g  142595 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.896  cc1              142596 142595   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.924  as               142597 142595   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.936  aarch64-linux-g  142598 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.938  cc1              142599 142598   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.979  as               142600 142598   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.994  aarch64-linux-g  142601 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.996  cc1              142602 142601   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.023  as               142603 142601   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.036  aarch64-linux-g  142604 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.038  cc1              142605 142604   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.065  as               142606 142604   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.077  aarch64-linux-g  142607 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.079  cc1              142608 142607   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.105  as               142609 142607   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.118  aarch64-linux-g  142610 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.119  cc1              142611 142610   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.146  as               142614 142610   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.159  aarch64-linux-g  142615 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.161  cc1              142617 142615   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.189  as               142618 142615   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.196  runc             142620 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup kill --all c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 9\n18.205  aarch64-linux-g  142626 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.208  cc1              142627 142626   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.216  runc             142628 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup delete c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n18.254  as               142635 142626   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.272  aarch64-linux-g  142637 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.275  cc1              142638 142637   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.310  as               142640 142637   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.322  aarch64-linux-g  142643 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.324  cc1              142644 142643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.358  as               142647 142643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.371  aarch64-linux-g  142648 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.373  cc1              142649 142648   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.392  containerd-shim  142652 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e delete\n18.398  runc             142659 142652   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e94 --log-format json delete --force c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n18.412  as               142664 142648   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.429  aarch64-linux-g  142665 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.433  cc1              142667 142665   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.436  systemd-sysctl   142668 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe7f190c --prefix=/net/ipv4/neigh/vethe7f190c --prefix=/net/ipv6/conf/vethe7f190c --prefix=/net/ipv6/neigh/vethe7f190c\n18.489  as               142674 142665   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.512  aarch64-linux-g  142676 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.516  cc1              142678 142676   0 \n18.563  as               142682 142676   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.590  aarch64-linux-g  142684 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.596  cc1              142685 142684   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.648  as               142690 142684   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.667  aarch64-linux-g  142692 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.670  cc1              142694 142692   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.714  as               142697 142692   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.734  aarch64-linux-g  142699 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.737  cc1              142700 142699   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.776  as               142704 142699   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.795  aarch64-linux-g  142706 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.800  cc1              142707 142706   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n"
}
```

#### Record 28

```json
{
  "argv": [
    "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 136475,
  "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build",
  "pid": 136475,
  "ppid": 136274,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/out"
}
```

#### Record 29

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 136475,
  "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 136476,
  "ppid": 136475,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_build_script_out_dir": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/out",
  "_direct_build_script_child": true,
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 30

```json
{
  "argv": [
    "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "build-script-bu",
  "event": "process_exec",
  "image": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build",
  "pid": 137043,
  "ppid": 136274,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out"
}
```

#### Record 31

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-E",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family."
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 137044,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 32

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
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family.",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-fstack-protector-strong",
    "-Wformat",
    "-Wformat-security",
    "-dumpbase",
    "17123910858420338620detect_compiler_family.c",
    "-dumpbase-ext",
    ".c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 137045,
  "ppid": 137044,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 33

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-gcc",
    "-?"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 137048,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 34

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
    "-Wall",
    "-Wextra",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
    "-c",
    "src/errno.c"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-gcc",
  "pid": 137049,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 35

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
    "-quiet",
    "-imultilib",
    ".",
    "-imultiarch",
    "riscv64-linux-gnu",
    "src/errno.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/",
    "-dumpbase",
    "ea708c7824d36062-errno.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "cc1",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
  "pid": 137050,
  "ppid": 137049,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 36

```json
{
  "argv": [
    "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
    "--gdwarf-4",
    "--traditional-format",
    "-fpic",
    "-march=rv64gc",
    "-march=rv64imafdc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-o",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
    "/tmp/ccDdfoDN.s"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "as",
  "event": "process_exec",
  "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
  "pid": 137052,
  "ppid": 137049,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 37

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 137054,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 38

```json
{
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "sD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a"
  ],
  "build_script_related": true,
  "build_script_root_pid": 137043,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "comm": "riscv64-linux-g",
  "event": "process_exec",
  "image": "/usr/bin/riscv64-linux-gnu-ar",
  "pid": 137056,
  "ppid": 137043,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_cwd_recovered_from_build_script_run": true
}
```

#### Record 39

```json
{
  "crate": "libc",
  "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "event_id": "bsrun:a733304fa0307800:44908145cb21c910:12dd80fa150623bf",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
  "out_dir": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/out",
  "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
  "success": true,
  "target": null,
  "version": "0.2.186",
  "_owner": {
    "crate": "libc",
    "version": "0.2.186",
    "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
    "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
    "source": "cwd_prefix"
  }
}
```

#### Record 40

```json
{
  "crate": "errno-dragonfly",
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "event_id": "bsrun:660492fcc3b28119:da1365b89f3a9aa8:93e4a5a24c4f8cbe",
  "evidence_kind": "exec_context_out_dir_inferred",
  "exe": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build",
  "host": null,
  "kind": "build_script_run",
  "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
  "success": true,
  "target": null,
  "version": "0.1.2",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  }
}
```

#### Record 41

```json
{
  "argv": [
    "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
    "--version"
  ],
  "build_script_related": true,
  "build_script_root_pid": 136475,
  "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
  "comm": "rustc",
  "event": "process_exec",
  "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
  "pid": 136476,
  "ppid": 136475,
  "root_cargo_pid": 136274,
  "source": "linux_ebpf:/usr/local/bin/execsnoop",
  "kind": "rustc_exec",
  "tool": "rustc",
  "cargo_related": true,
  "rustc_related": true
}
```

#### Record 42

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
    "src/errno.c",
    "-quiet",
    "-dumpdir",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/",
    "-dumpbase",
    "ea708c7824d36062-errno.c",
    "-dumpbase-ext",
    ".c",
    "-march=rv64gc",
    "-mabi=lp64d",
    "-misa-spec=2.2",
    "-march=rv64imafdc",
    "-g",
    "-gdwarf-4",
    "..."
  ],
  "src": "src/errno.c",
  "output": "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
  "success": true,
  "evidence_source": "process_exec_cc1_and_sibling_as",
  "recovered_from_process_exec": true,
  "pid": 137050,
  "ppid": 137049,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "root_cargo_pid": 136274,
  "build_script_root_pid": 137043,
  "build_script_related": true,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_cwd_recovered_from_compiler_parent": true
}
```

#### Record 43

```json
{
  "event": "archive",
  "tool": "/usr/bin/riscv64-linux-gnu-ar",
  "real_tool": "/usr/bin/riscv64-linux-gnu-ar",
  "argv": [
    "/usr/bin/riscv64-linux-gnu-ar",
    "cqD",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
  ],
  "archive": "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
  "objects": [
    "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
  ],
  "success": true,
  "evidence_source": "process_exec_argv",
  "recovered_from_process_exec": true,
  "argv_truncated": false,
  "pid": 137054,
  "ppid": 137043,
  "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "root_cargo_pid": 136274,
  "build_script_root_pid": 137043,
  "build_script_related": true,
  "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
  "_owner": {
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
    "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
    "source": "cwd_prefix"
  },
  "_build_script_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
  "_build_script_out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
  "_direct_build_script_child": true,
  "_cwd_recovered_from_build_script_run": true
}
```

## Original input record

This is the untouched JSONL object loaded from `successes*.jsonl` before recovery and enrichment.

```json
{
  "time": "2026-07-14T01:37:42.348966+00:00",
  "crate": "errno-dragonfly",
  "version": "0.1.2",
  "architecture": "riscv64",
  "duration_seconds": 26.655510316137224,
  "trace_record_count": 40,
  "trace_owner_summary": {
    "owner_package_count": 5,
    "owner_packages": [
      {
        "crate": "find-msvc-tools",
        "version": "0.1.9",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml"
      },
      {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml"
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
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "manifest_path": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/Cargo.toml"
      }
    ],
    "attributed_event_count": 27,
    "unattributed_event_count": 13,
    "owners": [
      {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
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
        "version": "0.2.186",
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
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "cargo_args": [
        "build",
        "--target",
        "riscv64gc-unknown-linux-gnu"
      ],
      "workspace_default_members": [
        "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2"
      ],
      "packages": [
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#cc@1.2.67",
          "name": "cc",
          "version": "1.2.67",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/cc-1.2.67"
        },
        {
          "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
          "name": "errno-dragonfly",
          "version": "0.1.2",
          "manifest_path": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2/Cargo.toml",
          "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#find-msvc-tools@0.1.9",
          "name": "find-msvc-tools",
          "version": "0.1.9",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/find-msvc-tools-0.1.9"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
          "name": "libc",
          "version": "0.2.186",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186"
        },
        {
          "package_id": "registry+https://github.com/rust-lang/crates.io-index#shlex@2.0.1",
          "name": "shlex",
          "version": "2.0.1",
          "manifest_path": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1/Cargo.toml",
          "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/shlex-2.0.1"
        }
      ],
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cwd_prefix"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "kind": "exec",
      "pid": 136428,
      "ppid": 136329,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:8bcf3eff2fa52fa3:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
      "pid": 136428,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:2a6962d9700b3a6f:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
      "pid": 136428,
      "sha256": "64eb7fc5099e1948e306f9c8a523b826941e7f6f829933101392444b06b4538e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:f90a82b8b08a57e8:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
      "pid": 136428,
      "sha256": "e5617ac33c84f22a8b2a806d2362095876748795e0fc941671566e69acc805b4",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:0ce2bb3a4c72bd09:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
      "pid": 136428,
      "sha256": "1fd12f1851556a6df4ee5c71d6fe92d121e5a11cebbbfa97cc71ba46b14b7692",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:2039e6bbdc279ca3:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
      "pid": 136428,
      "sha256": "d112027f03bd03220f5b546fa33b20cb5c6eed11120d0c291cc6bd2ddb069f48",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "consumer_kind": "linker",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "used:cc:f7a275179e4f3c0d:8c799a9b888348bf:1d8ed5dafb3ff8ae",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
      "pid": 136428,
      "sha256": "c668b521a73e76c017ee2e7b87ff814174e0875a9f9435ddba2cfb922d96224a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
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
      "output": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "cargo_pkg_name": "libc",
      "cargo_pkg_version": "0.2.186",
      "context_path": "/tmp/native-trace-135773-1783993040646/events/00000000-root-context.jsonl",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-135773-1783993040646/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 136428,
      "ppid": 136329,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN",
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
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
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/rustcaFqaHN/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.0.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.1.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.2.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.build_script_build.596225a9db1ae3c-cgu.3.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/libc-a4e3fe6c6f3e6c4a",
          "kind": "object",
          "path": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build_script_build-a4e3fe6c6f3e6c4a.e03gl7vs1cco917adhqp5y5xm.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-136428-1783993043507949365.map",
      "pid": 136428,
      "ppid": 136329,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-136428-1783993043507949365.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "exit_code": 0,
      "kind": "exec",
      "pid": 137022,
      "ppid": 136999,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:a3eee9239f84efe8:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
      "pid": 137022,
      "sha256": "3c88e92332b7de39df5e21839e0ebb7ea3e6b5a5fbf56759e2017a26052cbe77",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:c1ed862cfff17b95:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "65e02699a94199f2c9ed5d6158e35de9100f8753d2fd0bba971c5b0895b605c9",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:e19c0dbd7ca62cf6:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "125f0a189ff3efd09e679b70519393d390b94ee4afe664fbe5974b484b95bb4f",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:fa2fc1ad4a9984bf:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "0c2384bc5e11cc2d2fdf72c0e7ad95e9ba1241acbaabe5c8b33e1c67a8e7da0a",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:1169987e729c8448:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "a2323576c6a9583ad720f21ed2a56bfc76534c2eb55b36ad31da5d9895cd5e85",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:2464d7a65ccdf87f:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "459fe9487d3e51d8e2bfd5ca6161e8027c7e2a3b23d207ec3a5b897e9fe7fa4c",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:af709c13fa82b83e:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "edcdb51dee83aeb25a2812ed65bb57727b09a4331569aa6d0d354bab69d5d66e",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:6f6e8110127f9770:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "73b025275731d5cd76e415e614f692ad7ac56412c666518242c84996dd80d718",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:afb66abb860c3d3a:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "bdf4fd06abe8b1d5a343d9c3fc93b4eb4954dd5c6269eb0831d66a543c40ca58",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "consumer_kind": "linker",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "used:cc:46febdad91dc0cb4:df35bd192616d580:ba5e1f9bac558b7d",
      "exit_code": 0,
      "input_kind": "object",
      "kind": "used_input",
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
      "pid": 137022,
      "sha256": "d3c9e177b473c32b15bc199e76757f875156b8baf830111ebdd5dd71e46ea7a7",
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "exit_code": 0,
      "inputs": [
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o"
      ],
      "kind": "link",
      "lib_paths": [
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
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
      "output": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
      "shared": false,
      "static_link": false,
      "success": true,
      "tool": "cc",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cargo_manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "cargo_pkg_name": "errno-dragonfly",
      "cargo_pkg_version": "0.1.2",
      "context_path": "/tmp/native-trace-135773-1783993040646/events/00000000-root-context.jsonl",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "exit_code": 0,
      "host": null,
      "kind": "exec_context",
      "metadata_path": "/tmp/native-trace-135773-1783993040646/events/00000000-cargo-metadata.json",
      "num_jobs": null,
      "opt_level": null,
      "out_dir": null,
      "pid": 137022,
      "ppid": 136999,
      "profile": null,
      "real_tool": "/usr/bin/cc",
      "root_cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "success": true,
      "target": null,
      "tool": "cc",
      "workspace_root": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
        "source": "cargo_manifest_dir"
      }
    },
    {
      "argv": [
        "cc",
        "-m64",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/raw-dylibs",
        "-B/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld",
        "-fuse-ld=lld",
        "-Wl,--eh-frame-hdr",
        "-Wl,-z,noexecstack",
        "-L",
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/lib",
        "-o",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395",
        "-Wl,--gc-sections",
        "-pie",
        "-Wl,-z,relro,-z,now",
        "-nodefaultlibs"
      ],
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "directories": [
        "/usr/lib/gcc/x86_64-linux-gnu/11/../../../x86_64-linux-gnu",
        "/usr/lib/gcc/x86_64-linux-gnu/11",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
        "/target/debug/build/errno-dragonfly-230bb91007c5e395",
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
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/rustcDSR4xQ/symbols.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0kum6ebs91ymojd3w8ua0r7sy.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.0xhe5dzakn7oynh8htt5n59jj.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.2q1qp3pbt8k6vrr42ogoof9db.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.6au7mgx4t68hk0tn4x6yi9dl6.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7rugos0p64skwj00r86i9hv1c.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.99quqfc70j5w5576a2nh8trrk.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.9x10186wt45w8l74ebtv6n9ef.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.da4iprr95c9b0npw46835ym2e.0fdb1nc.rcgu.o",
          "source": "link_trace"
        },
        {
          "directory": "/target/debug/build/errno-dragonfly-230bb91007c5e395",
          "kind": "object",
          "path": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build_script_build-230bb91007c5e395.7x3ehmglc9nbt1qr3owl5y32y.0fdb1nc.rcgu.o",
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
      "map_path": "/tmp/native-trace-link-cc-137022-1783993044724710478.map",
      "pid": 137022,
      "ppid": 136999,
      "real_tool": "/usr/bin/cc",
      "success": true,
      "tool": "cc",
      "trace_args": [
        "-Wl,--trace",
        "-Wl,-Map,/tmp/native-trace-link-cc-137022-1783993044724710478.map"
      ],
      "trace_mode": "driver",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
      "parsed_event_count": 1197,
      "phase": "stop",
      "platform": "linux_ebpf",
      "raw_event_count": 1199,
      "spawn_error": null,
      "stderr": "In file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:64:9: warning: '__HAVE_BUILTIN_BSWAP32__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP32__\n        ^\n<command line>:4:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP32__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:65:9: warning: '__HAVE_BUILTIN_BSWAP64__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP64__\n        ^\n<command line>:5:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP64__ 1\n        ^\nIn file included from <built-in>:2:\nIn file included from /virtual/include/bcc/bpf.h:12:\nIn file included from include/linux/types.h:6:\nIn file included from include/uapi/linux/types.h:14:\nIn file included from include/uapi/linux/posix_types.h:5:\nIn file included from include/linux/stddef.h:5:\nIn file included from include/uapi/linux/stddef.h:6:\nIn file included from include/linux/compiler_types.h:184:\ninclude/linux/compiler-clang.h:66:9: warning: '__HAVE_BUILTIN_BSWAP16__' macro redefined [-Wmacro-redefined]\n#define __HAVE_BUILTIN_BSWAP16__\n        ^\n<command line>:3:9: note: previous definition is here\n#define __HAVE_BUILTIN_BSWAP16__ 1\n        ^\nIn file included from <built-in>:3:\nIn file included from /virtual/include/bcc/helpers.h:53:\nIn file included from include/linux/log2.h:12:\nIn file included from include/linux/bitops.h:28:\nIn file included from include/asm-generic/bitops/generic-non-atomic.h:7:\nIn file included from arch/x86/include/asm/barrier.h:5:\nIn file included from arch/x86/include/asm/alternative.h:9:\nIn file included from arch/x86/include/asm/bug.h:108:\nIn file included from include/asm-generic/bug.h:22:\nIn file included from include/linux/printk.h:8:\nIn file included from include/linux/linkage.h:8:\nIn file included from arch/x86/include/asm/linkage.h:6:\narch/x86/include/asm/ibt.h:77:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr bool is_endbr(u32 *val);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:78:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr u64 ibt_save(bool disable);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\narch/x86/include/asm/ibt.h:79:8: warning: 'nocf_check' attribute ignored; use -fcf-protection to enable the attribute [-Wignored-attributes]\nextern __noendbr void ibt_restore(u64 save);\n       ^\narch/x86/include/asm/ibt.h:32:34: note: expanded from macro '__noendbr'\n#define __noendbr       __attribute__((nocf_check))\n                                       ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_current_task);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:85:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:12:\narch/x86/include/asm/current.h:23:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:84:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\n                return this_cpu_read_const(const_cpu_current_top_of_stack);\n                       ^\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:30: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n                                    ^\nnote: (skipping 4 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:56:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:3:\nIn file included from include/linux/sched.h:13:\narch/x86/include/asm/processor.h:554:10: warning: multiple identical address spaces specified for type [-Wduplicate-decl-specifier]\narch/x86/include/asm/percpu.h:559:36: note: expanded from macro 'this_cpu_read_const'\n#define this_cpu_read_const(pcp)                        __raw_cpu_read_const(pcp)\n                                                        ^\narch/x86/include/asm/percpu.h:147:35: note: expanded from macro '__raw_cpu_read_const'\n#define __raw_cpu_read_const(pcp)       __raw_cpu_read(, , pcp)\n                                        ^\narch/x86/include/asm/percpu.h:139:9: note: expanded from macro '__raw_cpu_read'\n        *(qual __my_cpu_type(pcp) *)__my_cpu_ptr(&(pcp));               \\\n               ^\nnote: (skipping 3 expansions in backtrace; use -fmacro-backtrace-limit=0 to see all)\ninclude/linux/args.h:25:24: note: expanded from macro '__CONCAT'\n#define __CONCAT(a, b) a ## b\n                       ^\n<scratch space>:55:1: note: expanded from here\n__seg_gs\n^\n<built-in>:309:33: note: expanded from here\n#define __seg_gs __attribute__((address_space(256)))\n                                ^\nIn file included from /virtual/main.c:4:\ninclude/linux/fs.h:1258:27: warning: unknown attribute '__counted_by__' ignored [-Wunknown-attributes]\n        unsigned char f_handle[] __counted_by(handle_bytes);\n                                 ^\ninclude/linux/compiler_types.h:381:47: note: expanded from macro '__counted_by'\n# define __counted_by(member)           __attribute__((__counted_by__(member)))\n                                                       ^\n11 warnings generated.\nNATIVE_TRACE_EXECSNOOP_READY\n",
      "stdout": " rustc            141880 141497   0 /home/xmoe/.cargo/bin/rustc --print sysroot\n16.252  docker           141897 141331   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.254  rustc            141878 141609   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.266  rustc            141880 141497   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --print sysroot\n16.271  docker           141916 141609   0 /usr/bin/docker --help\n16.284  build-script-bu  141926 141141   0 /target/debug/build/ahash-513e4052a7199891/build-script-build\n16.294  rustc            141935 141926   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --verbose --version\n16.297  docker           141936 141497   0 /usr/bin/docker --help\n16.307  rustc            141940 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name proc_macro2 --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/proc-macro2-1.0.106/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.308  docker           141941 141609   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.331  runc             141967 1599     0 /usr/bin/runc --version\n16.336  docker           141971 141497   0 /usr/bin/docker version -f {{ .Server.Os }},,,{{ .Server.Arch }}\n16.339  docker-init      141977 1599     0 /usr/bin/docker-init --version\n16.342  docker           141981 141609   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.347  systemd-sysctl   141987 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth462e707 --prefix=/net/ipv4/neigh/veth462e707 --prefix=/net/ipv6/conf/veth462e707 --prefix=/net/ipv6/neigh/veth462e707\n16.350  systemd-sysctl   141988 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth169aacc --prefix=/net/ipv4/neigh/veth169aacc --prefix=/net/ipv6/conf/veth169aacc --prefix=/net/ipv6/neigh/veth169aacc\n16.362  runc             141995 1599     0 /usr/bin/runc --version\n16.368  docker-init      142001 1599     0 /usr/bin/docker-init --version\n16.369  runc             142002 1599     0 \n16.380  docker-init      142008 1599     0 /usr/bin/docker-init --version\n16.384  docker           142009 141497   0 /usr/bin/docker info -f {{.SecurityOptions}}\n16.391  containerd-shim  142015 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c start\n16.397  rustc            142019 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.401  containerd-shim  142030 142015   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c -address /var/run/docker/containerd/containerd.sock\n16.401  rustup           142031 141609   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.403  rustc            142026 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.404  runc             142040 142030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c\n16.409  runc             142054 1599     0 /usr/bin/runc --version\n16.413  rustup           142063 141609   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.413  exe              142066 142040   0 /proc/self/exe init\n16.416  docker-init      142068 1599     0 /usr/bin/docker-init --version\n16.440  rustc            142083 140648   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name build_script_build --edition=2018 build.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type bin --emit=dep-info,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"static\")) -C metadata=90b92fb64bbd87d9 ...\n16.450  rustup           142093 141609   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.450  rustup           142092 141497   0 /home/xmoe/.cargo/bin/rustup toolchain list\n16.461  rustup           142114 141497   0 /home/xmoe/.cargo/bin/rustup target list --toolchain stable-x86_64-unknown-linux-gnu\n16.474  exe              142125 142040   0 /proc/1599/exe -exec-root=/var/run/docker 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c d7da31e8f8e1\n16.496  uname            142134 141609   0 /usr/bin/uname -r\n16.499  rustup           142135 141497   0 /home/xmoe/.cargo/bin/rustup component list --toolchain stable-x86_64-unknown-linux-gnu\n16.514  exe              142146 1599     0 /proc/self/exe /var/run/docker/netns/005e12871cc2 all false\n16.526  docker           142152 141609   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.537  uname            142160 141497   0 /usr/bin/uname -r\n16.564  rustc            142171 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.572  docker           142176 141497   0 /usr/bin/docker run --userns host --privileged --pid=host --security-opt seccomp=unconfined --ulimit memlock=-1:-1 -v /lib/modules:/lib/modules:ro -v /usr/src:/usr/src:ro -v /usr/src/kernels/6.18.10-100.fc42.x86_64:/usr/src/kernels/6.18.10-100.fc42.x86_64:ro -v /sys/fs/bpf:/sys/fs/bpf:rw -v /sys/kernel/debug:/sys/kernel/debug:rw ...\n16.591  runc             142205 142030   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be6 --log-format json --systemd-cgroup start 8d917af0399e06f724112d5d4500bb91c7332e80202690077ab33822be64900c\n16.600  systemd-sysctl   142215 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth6a03aef --prefix=/net/ipv4/neigh/veth6a03aef --prefix=/net/ipv6/conf/veth6a03aef --prefix=/net/ipv6/neigh/veth6a03aef\n16.602  sh               142085 142030   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.602  systemd-sysctl   142217 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vetha3ef1ab --prefix=/net/ipv4/neigh/vetha3ef1ab --prefix=/net/ipv6/conf/vetha3ef1ab --prefix=/net/ipv6/neigh/vetha3ef1ab\n16.603  cargo            142220 142085   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.624  cargo-native-tr  142220 142085   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target powerpc64le-unknown-linux-gnu\n16.629  cargo            142238 142220   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.648  containerd-shim  142257 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 start\n16.651  rustc            142259 142238   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.653  containerd-shim  142268 142257   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 -address /var/run/docker/containerd/containerd.sock\n16.658  runc             142277 142268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619\n16.664  cc               142283 142083   0 /tmp/native-trace-140328-1783993055854/shims/cc -m64 /target/debug/build/lzma-sys-5c2d69c993aabfec/rustce2Yd57/symbols.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.0emzgrjz0mbyz0ub8m5kx31rw.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.187gf3rk9m02q37c41q8g47of.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1iol46f9eey230dngrt6dfk7a.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1vig8wx5w91kvz3m9coj07849.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1z4p4hm1b81ngojvpej1tkj3b.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2bx6tmmw6rbv54jkfxabmqaqr.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ds6mcm4sy54wpwon2pfzz7em.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ecl7lbofydiczussh3a6t99m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2gcdf4joxpngceva48u1itnne.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.30x6duc672p5ev99dq8q3ox85.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.31tf5rfl0pi4nq6aipe6f7f70.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.33pc1db836fpagekeyle2f84m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.34gye9xshswyamigntl2p748y.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3b7x7fj1g5vox39qkt0u0x1lz.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3h9ckas9gbm05a2u3v7xt2r96.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3nhkxpupblrm2ni7qc1iu05v7.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.492iydcghkt8blkq5e79csf9l.1it1kcv.rcgu.o ...\n16.666  exe              142290 142277   0 /proc/self/exe init\n16.667  cc               142291 142283   0 /usr/bin/cc -m64 /target/debug/build/lzma-sys-5c2d69c993aabfec/rustce2Yd57/symbols.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.0emzgrjz0mbyz0ub8m5kx31rw.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.187gf3rk9m02q37c41q8g47of.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1iol46f9eey230dngrt6dfk7a.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1vig8wx5w91kvz3m9coj07849.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.1z4p4hm1b81ngojvpej1tkj3b.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2bx6tmmw6rbv54jkfxabmqaqr.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ds6mcm4sy54wpwon2pfzz7em.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2ecl7lbofydiczussh3a6t99m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.2gcdf4joxpngceva48u1itnne.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.30x6duc672p5ev99dq8q3ox85.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.31tf5rfl0pi4nq6aipe6f7f70.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.33pc1db836fpagekeyle2f84m.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.34gye9xshswyamigntl2p748y.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3b7x7fj1g5vox39qkt0u0x1lz.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3h9ckas9gbm05a2u3v7xt2r96.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.3nhkxpupblrm2ni7qc1iu05v7.1it1kcv.rcgu.o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec.492iydcghkt8blkq5e79csf9l.1it1kcv.rcgu.o ...\n16.675  rustc            142287 142238   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.675  collect2         142295 142291   0 /usr/lib/gcc/x86_64-linux-gnu/9/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -fuse-ld=lld -z relro -o ...\n16.675  systemd-sysctl   142294 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/veth15404de --prefix=/net/ipv4/neigh/veth15404de --prefix=/net/ipv6/conf/veth15404de --prefix=/net/ipv6/neigh/veth15404de\n16.675  systemd-sysctl   142293 138512   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethede48fb --prefix=/net/ipv4/neigh/vethede48fb --prefix=/net/ipv6/conf/vethede48fb --prefix=/net/ipv6/neigh/vethede48fb\n16.680  ld.lld           142296 142295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/gcc-ld/ld.lld -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o /target/debug/build/lzma-sys-5c2d69c993aabfec/build_script_build-5c2d69c993aabfec ...\n16.680  rust-lld         142296 142295   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/lib/rustlib/x86_64-unknown-linux-gnu/bin/rust-lld -flavor gnu -plugin /usr/lib/gcc/x86_64-linux-gnu/9/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/9/lto-wrapper -plugin-opt=-fresolution=/tmp/cc10cDPx.res --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro ...\n16.695  containerd-shim  142301 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa start\n16.700  execsnoop        142321 142220   0 /usr/local/bin/execsnoop -t\n16.701  python3          142321 142220   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n16.703  containerd-shim  142326 142301   0 /usr/bin/containerd-shim-runc-v2 -namespace moby -id 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa -address /var/run/docker/containerd/containerd.sock\n16.713  runc             142341 142326   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --log-format json --systemd-cgroup create --bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --pid-file /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa\n16.713  rustc            142331 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name quote --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/quote-1.0.46/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"default\" --cfg feature=\"proc-macro\" --check-cfg cfg(docsrs,test) ...\n16.727  exe              142349 142341   0 /proc/self/exe init\n16.759  exe              142370 142277   0 /proc/1599/exe -exec-root=/var/run/docker 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619 d7da31e8f8e1\n16.768  exe              142376 142341   0 /proc/1599/exe -exec-root=/var/run/docker 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa d7da31e8f8e1\n16.797  rustc            142387 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=35aaec97f13a8ad6 ...\n16.804  exe              142392 1599     0 /proc/self/exe /var/run/docker/netns/fd6470ee62b8 all false\n16.812  exe              142403 1599     0 /proc/self/exe /var/run/docker/netns/701b52d0100d all false\n16.818  git              142393 2235138   0 /usr/bin/git check-ignore -v -z --stdin\n16.859  build-script-bu  142420 140648   0 /target/debug/build/lzma-sys-5c2d69c993aabfec/build-script-build\n16.862  pkg-config       142421 142420   0 /tmp/native-trace-140328-1783993055854/shims/pkg-config --libs --cflags liblzma\n16.864  pkg-config       142422 142421   0 /usr/bin/pkg-config --libs --cflags liblzma\n16.872  aarch64-linux-g  142423 142420   0 /usr/bin/aarch64-linux-gnu-gcc -E /target/aarch64-unknown-linux-gnu/debug/build/lzma-sys-3402062eb38469a1/out/15694474413922396716detect_compiler_family.c\n16.875  cc1              142424 142423   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -E -quiet -imultiarch aarch64-linux-gnu /target/aarch64-unknown-linux-gnu/debug/build/lzma-sys-3402062eb38469a1/out/15694474413922396716detect_compiler_family.c -mlittle-endian -mabi=lp64 -fasynchronous-unwind-tables -fstack-protector-strong -Wformat -Wformat-security -fstack-clash-protection\n16.883  runc             142429 142268   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a --log-format json --systemd-cgroup start 61504fd17b2b6420a4ac5e4b646c917724cba6430931cdf089992765e5a37619\n16.883  aarch64-linux-g  142430 142420   0 /usr/bin/aarch64-linux-gnu-gcc -?\n16.888  rustc            142431 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name syn --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/syn-1.0.109/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"clone-impls\" --cfg feature=\"default\" --cfg feature=\"derive\" ...\n16.893  aarch64-linux-g  142432 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n16.896  cc1              142442 142432   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n16.900  sh               142352 142268   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.903  cargo            142446 142352   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target aarch64-unknown-linux-gnu\n16.903  rustc            142441 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=bdd4007228ca136e ...\n16.911  runc             142452 142326   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b1040 --log-format json --systemd-cgroup start 97ceece7dc2741d420d712ef92900d7e55b259cd5aeed47fafc184b104028eaa\n16.916  rustc            142451 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=917cf36d7c182416 ...\n16.921  cargo-native-tr  142446 142352   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target aarch64-unknown-linux-gnu\n16.921  sh               142362 142326   0 /usr/bin/sh -c PATH=\"$PATH\":\"/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin\":\"/home/xmoe/.cargo/bin\" cargo native-trace -- b\n16.922  cargo            142463 142362   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.925  cargo            142465 142446   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.937  cargo-native-tr  142463 142362   0 /home/xmoe/.cargo/bin/cargo-native-trace native-trace -- build --target riscv64gc-unknown-linux-gnu\n16.943  as               142470 142432   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n16.944  cargo            142472 142463   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/cargo metadata --format-version 1\n16.947  rustc            142471 142465   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.958  rustc            142474 142472   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc -vV\n16.962  aarch64-linux-g  142476 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n16.962  rustc            142475 142465   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.964  cc1              142477 142476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n16.979  rustc            142482 142472   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc - --crate-name ___ --print=file-names --crate-type bin --crate-type rlib --crate-type dylib --crate-type cdylib --crate-type staticlib --crate-type proc-macro --print=sysroot --print=split-debuginfo --print=crate-name ...\n16.985  as               142483 142476   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n16.989  execsnoop        142485 142446   0 /usr/local/bin/execsnoop -t\n16.990  python3          142485 142446   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.001  aarch64-linux-g  142490 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.003  cc1              142491 142490   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.004  execsnoop        142492 142463   0 /usr/local/bin/execsnoop -t\n17.006  python3          142492 142463   0 /usr/bin/python3 /usr/local/lib/native-trace/execsnoop-real -t\n17.014  rustc            142498 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=85aba2bb86f02949 ...\n17.042  rustc            142506 140696   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.063  as               142511 142490   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.076  aarch64-linux-g  142512 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.078  cc1              142513 142512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.100  rustc            142517 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name getrandom --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/getrandom-0.2.17/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"compiler_builtins\", \"core\", \"custom\", \"js\", \"js-sys\", \"linux_disable_fallback\", \"rdrand\", \"rustc-dep-of-std -C metadata=ada5e235c1649296 ...\n17.111  as               142519 142512   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.121  rustc            142526 140763   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.129  aarch64-linux-g  142528 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.132  cc1              142529 142528   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.170  rustc            142536 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name ahash --edition=2018 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/ahash-0.7.8/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --check-cfg cfg(docsrs,test) --check-cfg cfg(feature, values(\"atomic-polyfill\", \"compile-time-rng\", \"const-random\", \"default\", \"serde\", \"std\")) -C metadata=bd1c4082384a6a98 ...\n17.175  as               142538 142528   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.189  aarch64-linux-g  142542 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.192  cc1              142543 142542   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.235  as               142544 142542   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.251  aarch64-linux-g  142545 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.254  cc1              142546 142545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.265  rustc            142550 141141   0 /home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc --crate-name hashbrown --edition=2021 /home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/hashbrown-0.12.3/src/lib.rs --error-format=json --json=diagnostic-rendered-ansi,artifacts,future-incompat --crate-type lib --emit=dep-info,metadata,link -C embed-bitcode=no -C debuginfo=2 --cfg feature=\"ahash\" --cfg feature=\"default\" --cfg feature=\"inline-more\" ...\n17.293  as               142555 142545   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.310  aarch64-linux-g  142556 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.313  cc1              142557 142556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.422  as               142558 142556   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.446  aarch64-linux-g  142559 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.449  cc1              142560 142559   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.501  as               142564 142559   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.515  aarch64-linux-g  142567 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.517  cc1              142569 142567   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.549  as               142570 142567   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.562  aarch64-linux-g  142571 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.564  cc1              142572 142571   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.597  as               142576 142571   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.611  aarch64-linux-g  142577 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.613  cc1              142578 142577   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.640  as               142579 142577   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.653  aarch64-linux-g  142580 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.655  cc1              142581 142580   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.691  as               142582 142580   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.706  aarch64-linux-g  142583 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.708  cc1              142584 142583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.742  as               142585 142583   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.756  aarch64-linux-g  142586 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.758  cc1              142587 142586   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.791  as               142588 142586   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.804  aarch64-linux-g  142589 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.806  cc1              142590 142589   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.837  as               142591 142589   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.850  aarch64-linux-g  142592 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.852  cc1              142593 142592   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.882  as               142594 142592   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.894  aarch64-linux-g  142595 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.896  cc1              142596 142595   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.924  as               142597 142595   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.936  aarch64-linux-g  142598 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.938  cc1              142599 142598   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n17.979  as               142600 142598   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n17.994  aarch64-linux-g  142601 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n17.996  cc1              142602 142601   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.023  as               142603 142601   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.036  aarch64-linux-g  142604 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.038  cc1              142605 142604   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.065  as               142606 142604   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.077  aarch64-linux-g  142607 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.079  cc1              142608 142607   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.105  as               142609 142607   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.118  aarch64-linux-g  142610 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.119  cc1              142611 142610   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.146  as               142614 142610   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.159  aarch64-linux-g  142615 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.161  cc1              142617 142615   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.189  as               142618 142615   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.196  runc             142620 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup kill --all c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 9\n18.205  aarch64-linux-g  142626 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.208  cc1              142627 142626   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.216  runc             142628 135438   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e --log-format json --systemd-cgroup delete c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n18.254  as               142635 142626   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.272  aarch64-linux-g  142637 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.275  cc1              142638 142637   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.310  as               142640 142637   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.322  aarch64-linux-g  142643 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.324  cc1              142644 142643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.358  as               142647 142643   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.371  aarch64-linux-g  142648 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.373  cc1              142649 142648   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.392  containerd-shim  142652 1663     0 /usr/bin/containerd-shim-runc-v2 -namespace moby -address /var/run/docker/containerd/containerd.sock -publish-binary /usr/bin/containerd -id c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944 -bundle /var/run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e delete\n18.398  runc             142659 142652   0 /usr/bin/runc --root /var/run/docker/runtime-runc/moby --log /run/docker/containerd/daemon/io.containerd.runtime.v2.task/moby/c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e94 --log-format json delete --force c5efd97d8b27b9f1bb1eb47d5f54faa5178dc6bb87a1f85dfbeb45e8a6e2e944\n18.412  as               142664 142648   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.429  aarch64-linux-g  142665 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.433  cc1              142667 142665   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.436  systemd-sysctl   142668 138493   0 /usr/lib/systemd/systemd-sysctl --prefix=/net/ipv4/conf/vethe7f190c --prefix=/net/ipv4/neigh/vethe7f190c --prefix=/net/ipv6/conf/vethe7f190c --prefix=/net/ipv6/neigh/vethe7f190c\n18.489  as               142674 142665   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.512  aarch64-linux-g  142676 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.516  cc1              142678 142676   0 \n18.563  as               142682 142676   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.590  aarch64-linux-g  142684 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.596  cc1              142685 142684   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.648  as               142690 142684   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.667  aarch64-linux-g  142692 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.670  cc1              142694 142692   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.714  as               142697 142692   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.734  aarch64-linux-g  142699 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.737  cc1              142700 142699   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n18.776  as               142704 142699   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/../../../../aarch64-linux-gnu/bin/as -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common -I ...\n18.795  aarch64-linux-g  142706 142420   0 /usr/bin/aarch64-linux-gnu-gcc -O0 -ffunction-sections -fdata-sections -fPIC -g -gdwarf-4 -fno-omit-frame-pointer -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta ...\n18.800  cc1              142707 142706   0 /usr/lib/gcc-cross/aarch64-linux-gnu/9/cc1 -quiet -I xz-5.2/src/liblzma/api -I xz-5.2/src/liblzma/lzma -I xz-5.2/src/liblzma/lz -I xz-5.2/src/liblzma/check -I xz-5.2/src/liblzma/simple -I xz-5.2/src/liblzma/delta -I xz-5.2/src/liblzma/common -I xz-5.2/src/liblzma/rangecoder -I xz-5.2/src/common ...\n"
    },
    {
      "argv": [
        "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 136475,
      "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build",
      "pid": 136475,
      "ppid": 136274,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
        "--version"
      ],
      "build_script_related": true,
      "build_script_root_pid": 136475,
      "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 136476,
      "ppid": 136475,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "build-script-bu",
      "event": "process_exec",
      "image": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build",
      "pid": 137043,
      "ppid": 136274,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-E",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family."
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 137044,
      "ppid": 137043,
      "root_cargo_pid": 136274,
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
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/17123910858420338620detect_compiler_family.",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-fstack-protector-strong",
        "-Wformat",
        "-Wformat-security",
        "-dumpbase",
        "17123910858420338620detect_compiler_family.c",
        "-dumpbase-ext",
        ".c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 137045,
      "ppid": 137044,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-gcc",
        "-?"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 137048,
      "ppid": 137043,
      "root_cargo_pid": 136274,
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
        "-Wall",
        "-Wextra",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
        "-c",
        "src/errno.c"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-gcc",
      "pid": 137049,
      "ppid": 137043,
      "root_cargo_pid": 136274,
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
        "src/errno.c",
        "-quiet",
        "-dumpdir",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/",
        "-dumpbase",
        "ea708c7824d36062-errno.c",
        "-dumpbase-ext",
        ".c",
        "-march=rv64gc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-march=rv64imafdc",
        "-g",
        "-gdwarf-4",
        "..."
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "cc1",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/cc1",
      "pid": 137050,
      "ppid": 137049,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
        "--gdwarf-4",
        "--traditional-format",
        "-fpic",
        "-march=rv64gc",
        "-march=rv64imafdc",
        "-mabi=lp64d",
        "-misa-spec=2.2",
        "-o",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o",
        "/tmp/ccDdfoDN.s"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "as",
      "event": "process_exec",
      "image": "/usr/lib/gcc-cross/riscv64-linux-gnu/11/../../../../riscv64-linux-gnu/bin/as",
      "pid": 137052,
      "ppid": 137049,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "cqD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/ea708c7824d36062-errno.o"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 137054,
      "ppid": 137043,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "argv": [
        "/usr/bin/riscv64-linux-gnu-ar",
        "sD",
        "/target/riscv64gc-unknown-linux-gnu/debug/build/errno-dragonfly-2eeb40b975c28f3e/out/liberrno.a"
      ],
      "build_script_related": true,
      "build_script_root_pid": 137043,
      "build_script_target_dir": "errno-dragonfly-230bb91007c5e395",
      "comm": "riscv64-linux-g",
      "event": "process_exec",
      "image": "/usr/bin/riscv64-linux-gnu-ar",
      "pid": 137056,
      "ppid": 137043,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop"
    },
    {
      "crate": "libc",
      "cwd": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "event_id": "bsrun:a733304fa0307800:44908145cb21c910:12dd80fa150623bf",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
      "out_dir": "/target/debug/build/libc-a4e3fe6c6f3e6c4a/out",
      "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
      "success": true,
      "target": null,
      "version": "0.2.186",
      "_owner": {
        "crate": "libc",
        "version": "0.2.186",
        "package_id": "registry+https://github.com/rust-lang/crates.io-index#libc@0.2.186",
        "manifest_dir": "/home/xmoe/.cargo/registry/src/index.crates.io-1949cf8c6b5b557f/libc-0.2.186",
        "source": "cwd_prefix"
      }
    },
    {
      "crate": "errno-dragonfly",
      "cwd": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "event_id": "bsrun:660492fcc3b28119:da1365b89f3a9aa8:93e4a5a24c4f8cbe",
      "evidence_kind": "exec_context_out_dir_inferred",
      "exe": "/target/debug/build/errno-dragonfly-230bb91007c5e395/build-script-build",
      "host": null,
      "kind": "build_script_run",
      "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
      "out_dir": "/target/debug/build/errno-dragonfly-230bb91007c5e395/out",
      "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
      "success": true,
      "target": null,
      "version": "0.1.2",
      "_owner": {
        "crate": "errno-dragonfly",
        "version": "0.1.2",
        "package_id": "path+file:///tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2#errno-dragonfly@0.1.2",
        "manifest_dir": "/tmp/crate-build-riscv64-ac_zzwr9/src/errno-dragonfly-0.1.2",
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
      "build_script_root_pid": 136475,
      "build_script_target_dir": "libc-a4e3fe6c6f3e6c4a",
      "comm": "rustc",
      "event": "process_exec",
      "image": "/home/xmoe/.rustup/toolchains/stable-x86_64-unknown-linux-gnu/bin/rustc",
      "pid": 136476,
      "ppid": 136475,
      "root_cargo_pid": 136274,
      "source": "linux_ebpf:/usr/local/bin/execsnoop",
      "kind": "rustc_exec",
      "tool": "rustc",
      "cargo_related": true,
      "rustc_related": true
    }
  ],
  "item": {
    "rank": 671,
    "crate": "errno-dragonfly",
    "version": "0.1.2",
    "crate_id": "22896",
    "version_id": "430495",
    "downloads": 41615863,
    "cumulative_downloads": 79523181920,
    "cumulative_share_of_global": 0.2973188188098929,
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
